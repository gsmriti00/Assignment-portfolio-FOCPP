Objective:
The aim of this lab was to create my first web application using Flask and learn the basics of building web pages, handling user input, and displaying dynamic content with Python.

Steps I Followed:
First, I created a project folder and set up a virtual environment to keep all the project dependencies separate. Then, I installed Flask using pip and verified the installation. I started building my app by creating a file called app.py with a home page that displayed a simple welcome message. After that, I added more routes, such as /about and /greet, to create multiple pages. I then created a templates folder and added base.html as a layout template along with index.html and greet.html to reuse the design for all pages. On the Greet page, I added a form that allowed the user to enter their name, which the app then used to display a personalized greeting. I also included dynamic routes using URL variables, like /user/<name>, to demonstrate how pages could change based on user input. To improve the appearance, I created a static folder and added a CSS file to style the pages. Finally, I saved all project dependencies into a requirements.txt file using pip freeze, which ensures that anyone else can run the app easily.


Project Structure:

flask_hello_app/

├── venv/                
├── app.py                
├── requirements.txt      
├── templates/  

│   ├── base.html

│   ├── index.html

│   └── greet.html

└── static/

   └── style.css         

What I Learned:
Through this lab, I learned how to set up a virtual environment, create routes and pages in Flask, use templates for consistent layout, handle user input through forms, create dynamic content using URL variables, and style pages with CSS. I also learned how to save project dependencies for sharing.

Outcome:
By the end of the lab, I successfully built a working Flask web app with multiple pages, form handling, and styling. This project gave me a practical understanding of Flask and basic web development using Python.
