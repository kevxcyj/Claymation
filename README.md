# Claymation

Suntha Lucas, Suntha.Lucas@atlasschool.com
Kevin Cyrus Jr. Kevin.Cyrus@atlasschool.com

https://kevxcyj.github.io/Claymation/


Drumming Boy Claymation Animation
Description
This is a web-based project showcasing a Claymation animation theme with a particular focus on the beloved "The Little Drummer Boy" television special. It features:

A carousel that showcases different renditions of "The Little Drummer Boy" by various artists.
A snowfall animation to add a festive touch to the page.
An interactive dropdown menu that explains the art of Claymation, how it works, and what materials are commonly used, with a special section dedicated to the history of Claymation in popular culture.
The project utilizes HTML, CSS, Bootstrap, and JavaScript to create a smooth, engaging experience for the user.

Features
Snowfall Effect: Creates a dynamic wintery atmosphere using CSS keyframes and animation.
Carousel: Displays images of various renditions of "The Little Drummer Boy" in a rotating carousel.
Claymation Dropdown: A collapsible dropdown menu with information about Claymation animation, its materials, and history.
Responsive Design: The page adapts well to mobile and desktop views with Bootstrap's grid system.
Interactive Elements: Users can click on dropdown buttons to reveal information about Claymation.
Table of Contents
Installation
Usage
Contributing
License
Installation
To run this project locally on your machine, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/drumming-boy-claymation.git
Navigate to the project directory:

bash
Copy code
cd drumming-boy-claymation
Open the project in your browser: Simply open the index.html file in your browser to view the project.

Optionally, install any necessary dependencies (though this project does not require any external Node.js dependencies).

bash
Copy code
# If you have a local server setup
npm install
Usage
Interacting with the Page
Claymation Info Dropdown: Click on the "What Is Claymation?" dropdown to learn about Claymation, including what materials are used and its history.

Carousel: Browse through the images of different renditions of "The Little Drummer Boy" by various famous artists like Ray Conniff, Bert Kaempfert, and Frank Sinatra.

Snowfall Effect: Enjoy the dynamic snowfall animation that adds a whimsical touch to the background.

Responsive Design: The page adapts to both mobile and desktop screens. On smaller screens, the carousel will automatically adjust, and the content will be formatted for mobile devices.

Editing Content
You can update the carousel images by modifying the src attribute of the <img> tags inside the carousel section in the HTML.
To change the Claymation text, simply edit the content inside the <div id="what-is-claymation-content"> in the HTML.
Customizing the Snowflakes
If you'd like to adjust the snowfall:

Modify the CSS under the .snowflake and .snowflake .inner classes.
Adjust the animation-duration, animation-delay, or even the left position for more unique snowfall patterns.
Adjusting the Carousel Speed
You can control how quickly the carousel slides by modifying the data-bs-interval value in the carousel's HTML:

html
Copy code
<div id="multiCarousel" class="carousel slide" data-bs-interval="3000">
The value is in milliseconds (e.g., 3000 = 3 seconds). Set it to a larger number for slower movement.

Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps.
