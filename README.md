# CRUD-application-Flask
This a simple CRUD application developed using FLASK framework with MYSQLAlchemy

To create a CRUD (Create, Read, Update, Delete) web application using Flask, we will follow these steps:

Step 1: Set Up the Environment
First, ensure you have Flask and SQLAlchemy installed. You can install these via pip:
pip install Flask SQLAlchemy

Step 2: Create the Flask Application
Create a new file called app.py:

Step 3: Define the Database Model
Create a User model in app.py:

Step 4: Create CRUD Routes
Add routes for creating, reading, updating, and deleting users in app.py:

Step 5: Design HTML Templates
Create the following HTML templates:(create a folder names 'templates' and add below 2 html files into it

templates/index.html
templates/update.html

Step 6: Implement Security Best Practices
install flask-wtf
pip install Flask-WTF


This completes the basic implementation of a CRUD application using Flask. 

You can run this application by executing python app.py and navigating to http://127.0.0.1:5000 in your web browser.


#I used python 3.7 version
Make sure to install below packages before running the project 
on windows in command prompt:
pip install Flask
pip install SQLAlchemy
pip install Flask-WTF
pip install email_validator

steps to run this project in command prompt:
Navigate to Your Project Directory:

Open your command prompt.
Navigate to the directory where your app.py file is located. You can use the cd command to change directories.

Set the FLASK_APP Environment Variable:
Before running your Flask app, you need to set the FLASK_APP environment variable to point to your application. This can be done differently depending on your operating system.

set FLASK_APP=app.py

Run the Flask Application:
Now, you can run your Flask application using the following command:

flask run

This will start the Flask development server, and you should see output similar to:

* Serving Flask app "app.py"
* Environment: production
  WARNING: This is a development server. Do not use it in a production deployment.
  Use a production WSGI server instead.
* Debug mode: on
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

 Open your web browser and navigate to http://127.0.0.1:5000/ to see your CRUD application in action.

 








