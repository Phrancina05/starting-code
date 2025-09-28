## ReadMe File for Lab 5

# Web Application Development (WAD621S) Styling Lab - Lab 05
Design Decisions
1. Cards
•	Used rounded corners (border-radius) and shadows (box-shadow) for depth.

•	Added hover effects with smooth transitions (transition: all 0.3s ease) to make cards interactive.

•	Ensured images inside cards are responsive and maintain aspect ratio (object-fit: cover).

3. Buttons
•	Created a primary button using the main brand colour (--primary) and variants for success, warning, and info.

•	Implemented outline buttons for secondary actions.

•	Disabled buttons are styled with lighter colours and no pointer events for clarity.

•	Buttons with icons include proper spacing (padding and gap) for readability.

4. Chips
•	Chips are rounded (border-radius: 50px) to match modern UI trends.
•	Active chips have a different background colour for clarity.
•	Close buttons inside chips are styled for easy interaction.
5. Navigation
•	Horizontal navigation bar with hover effects and an active state indicator.
•	Flexbox used to space items evenly and maintain alignment.
•	Responsive behaviour ensures the nav bar adapts to smaller screens.
6. Forms
•	Styled input fields with focus states to guide the user.
•	Consistent spacing between labels and inputs.
•	Text areas and input boxes use the same border and background styles for uniformity.
7. Responsive Design
•	Grid layout adapts to different screen sizes using media queries.
•	Components stack vertically on small screens for better usability.
8. Advanced CSS Variables
•	Implemented a colour system with CSS variables to maintain a consistent theme.
•	Theme switching can be implemented easily by overriding variable values.

 Challenges Faced
1.	Maintaining consistency across components 
 Ensuring all buttons, cards, and chips had the same spacing and shadow style required careful attention to the CSS variables.
2.	Responsive design 
 Some components did not behave as expected on small screens initially; had to adjust grid and flex properties with media queries.
3.	Hover and active states 
 Adding smooth transitions while keeping performance optimal was a balancing act.
4.	Chips with icons 
 Aligning the close button and text inside the chip required fine-tuning of padding and line-height.

 Extension Challenges Attempted
1.	Interactive Animations 
 Added hover transitions on buttons and cards to enhance interactivity.
2.	Theme-ready design 
 Used CSS variables to make switching between light and dark modes possible in the future.
3.	Focus Styles for Accessibility 
 All form inputs have clear focus outlines for better accessibility.

