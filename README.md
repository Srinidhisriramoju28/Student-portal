flask_app/ │ ├── app.py # Flask app entry point ├── templates/ │ ├── home.html # Home page template │ ├── form.html # Form page template │ └── display.html # Display page template └── users.db Part 1: Python Script for Student Records We'll create a Python script that reads a CSV file containing student records (name, age, grade), calculates the average grade, and prints the student with the highest grade. Part 2: Web Development Using Flask We'll create a simple Flask web application that includes:

Home Page Form Page Display Page Simple API Endpoint Flask Setup Install Flask: pip install flask Part 3: Database Integration & User Authentication Now, we’ll extend this application to include database integration using SQLAlchemy (as seen above), and user authentication using Flask-Login.

Install the Required Libraries: pip install flask-login

steps to execute: 1.create student_record.py file 2.create students.csv 3.create a directory called flask_app 4.create app.py file under flask_app 5.create template folder under flask_app 6.create home.html,form.html,display.html finally database is created automatoically after installing flask packages 7.run app.py file a link is shown as output click the link.
