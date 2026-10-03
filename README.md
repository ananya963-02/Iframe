iFrame Assignment Navigation

A simple HTML and CSS project that demonstrates how to use an HTML "<iframe>" to display multiple assignments on the same webpage. A navigation panel on the left contains links, while the selected assignment is loaded inside the iframe on the right.

Features

- 🖼️ Uses an HTML "<iframe>"
- 📚 Contains links to 10 different assignments
- 🧭 Sidebar navigation
- 🔗 Uses the "target" attribute to load pages inside the iframe
- 🎨 Simple CSS styling
- 📐 Flexbox-based two-column layout
- 🖱️ Rounded navigation buttons

Technologies Used

- HTML5
- CSS3
- Flexbox
- HTML iframe

Project Structure

IFrame-Assignment/
│
├── index.html
├── assignment1.html
├── news paper assignment 2.html
├── assignment3.html
├── assignment4.html
├── assignment 5.html
├── Home.html
├── index.html
├── Assignement 8.html
├── Assignment 9 box plotting.html
├── Login.html
└── README.md

«Make sure all assignment files are located in the correct directory and their filenames match the links used in the HTML code.»

How to Run

1. Place the main HTML file and all assignment files in the same folder.
2. Open the main HTML file in a web browser.
3. You will see a navigation panel on the left side.
4. Click any assignment button.
5. The selected assignment will open inside the iframe on the right side.

Page Layout

The webpage is divided into two sections:

+----------------------+--------------------------------+
|                      |                                |
|    Assignment 1      |                                |
|    Assignment 2      |                                |
|    Assignment 3      |                                |
|    Assignment 4      |       Assignment Content       |
|    Assignment 5      |                                |
|    Assignment 6      |       <iframe>                 |
|    Assignment 7      |                                |
|    Assignment 8      |                                |
|    Assignment 9      |                                |
|    Assignment 10     |                                |
|                      |                                |
+----------------------+--------------------------------+
        Left                         Right

The left section contains navigation buttons, while the right section contains the iframe.

HTML iframe

The iframe is created using:

<iframe 
    src="" 
    frameborder="0" 
    height="100%" 
    width="100%" 
    name="box">
</iframe>

The iframe has the name "box", which allows links to target it.

Target Attribute

Each assignment link uses:

<a href="assignment1.html" target="box">
    Assignment1
</a>

The important part is:

target="box"

Because the iframe has:

name="box"

the linked page opens inside the iframe instead of replacing the entire webpage.

CSS Layout

The main container uses Flexbox:

.con {
    height: 600px;
    border: 1px solid black;
    display: flex;
}

The left navigation takes 30% of the available width:

.left {
    height: 100%;
    width: 30%;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
}

The iframe section takes 70%:

.right {
    height: 100%;
    width: 70%;
    border: 1px solid black;
}

Navigation Buttons

The assignment links are styled as rounded buttons:

.button {
    height: 8%;
    width: 90%;
    border: 1px solid black;
    border-radius: 30px;
    text-align: center;
    line-height: 40px;
    background-color: antiquewhite;
}

Assignments Included

The navigation provides links to:

Button| Target Page
Assignment 1| "assignment1.html"
Assignment 2| "news paper assignment 2.html"
Assignment 3| "assignment3.html"
Assignment 4| "assignment4.html"
Assignment 5| "assignment 5.html"
Assignment 6| "Home.html"
Assignment 7| "index.html"
Assignment 8| "Assignement 8.html"
Assignment 9| "Assignment 9 box plotting.html"
Assignment 10| "Login.html"

Learning Objectives

This project helps beginners understand:

- How to create an iframe
- How "<iframe>" works in HTML
- How the "name" attribute works
- How the "<a>" tag's "target" attribute works
- How to load different HTML pages inside an iframe
- Creating layouts with CSS Flexbox
- Creating navigation menus
- Using percentage-based widths and heights

Important Note

The iframe initially has an empty "src":

src=""

Therefore, no assignment is displayed until one of the navigation links is clicked.

Also, the project depends on the referenced HTML files being available at the specified paths.

Future Improvements

The project could be improved by:

- Adding hover effects to the buttons
- Adding active-button styling
- Making the layout responsive for mobile devices
- Adding a default assignment in the iframe
- Replacing "frameborder" with modern CSS
- Organizing assignment files into separate folders
- Adding icons to the navigation buttons

License

This project is free to use for learning and personal projects.# Iframe
