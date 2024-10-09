README
Project Title: Moving Colored Circles
Description
This project consists of an HTML document that creates a simple animation of colored circles moving within a defined area of the browser window. The circles bounce off the edges of the screen, changing direction randomly when they collide with the boundaries.
Features
•	Generates 10 randomly colored circles.
•	Each circle moves in a random direction and bounces off the walls of the containing area.
•	Circles are styled with a border and a smooth rounded shape.
Technologies Used
•	HTML5
•	CSS (inline styles)
•	JavaScript
How to Run
1.	Download or Clone the Repository: Download the HTML file or clone the repository to your local machine.
2.	Open in Browser: Open the HTML file in any modern web browser (e.g., Chrome, Firefox, Edge).
3.	View the Animation: You should see circles moving within a defined space, bouncing off the edges of the window.
Code Structure
•	The document contains a single <div> element that serves as the container for the animation.
•	JavaScript is used to create and animate the circles:
o	create() function: Creates a circle, assigns it a random color, and appends it to the document body.
o	randomColor() function: Returns a random color from a predefined palette.
o	Animation Logic: The move() function updates the position of each circle based on randomly generated velocities. The animation runs at intervals using setInterval.
Customization
•	You can modify the number of circles by changing the loop count in the for loop that populates the arr array.
•	The size of the circles can be changed in the create() function.
•	To change the colors, edit the palet array in the randomColor() function.
License
This project is open source and available for anyone to use and modify.
Acknowledgments
Feel free to modify this code for your own training, personal projects, or educational purposes!
