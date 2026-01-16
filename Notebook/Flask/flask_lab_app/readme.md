Objective:

The goal of this project was to build a full-featured Flask web application to practice Python fundamentals like functions, lists, forms, sessions, and role-based access control while learning web app development.


Steps I Followed:

I started by setting up a virtual environment and installing Flask using pip. I created the main file app.py and initialized the Flask app with routes for Home, Greet, Login, Logout, and Favorites pages.

On the Greet page, users can enter their name in a form, and the app displays a personalized greeting along with string operations like uppercase, lowercase, reversed text, and length.

On the Favorites page, I managed a list of programming languages with options to add, delete selected, clear, or sort languages. Admin users have extra permissions to delete or clear the list.

I implemented user authentication using a dummy database and Flask sessions to manage login/logout and control access based on user roles.

I used a templates folder to create HTML templates (base.html, index.html, greet.html, favorites.html, login.html) with template inheritance for consistent layout, and a static folder for CSS styling to make the app visually organized and user-friendly. Forms and dynamic content were rendered using Jinja2.


Project Structure:

flask_full_lab_app/

│
├── app.py               
├── requirements.txt    
├── templates/

│   ├── base.html
│   ├── index.html
│   ├── greet.html
│   ├── favorites.html
│   └── login.html

├── static/             
│   └── style.css

└── venv/            


What I Learned:

I learned how to build a Flask web application from scratch, use HTML templates and CSS styling, manage forms and user input, implement Python functions for data operations, handle sessions for login/logout, and control access based on user roles. I also practiced template inheritance, dynamic rendering, and user interaction.


Outcome:

By completing this project, I developed a fully functional Flask web app demonstrating multiple Python concepts in one integrated project. This gives me a strong foundation to build more advanced web applications in the future.
