# This directory contains assets for randoms.io
<p align="center"> <img width="286px" height="auto" src="./logo.png"> </p>

# Tasks
Capstone project for CS50's Web Programming with Python and JavaScript

## Features
- Easy to use To Do Task management
- Three choices for tasks
	+ To Do - for future tasks
	+ Work - tasks currently operating on
	+ Done - completed tasks 
- Change task type anytime
- Update or delete tasks
- Login and registeration system for isolating user data
- Facility to update password at anytime
- Fully responsive and adapts screen flow
- Made with Bulma CSS
- Django backend

## Motivation
I wanted to make a service for my self as I needed to separate the tasks assigned based on what I am supposed to do next, what I am currently working on and also to keep a record of projects and tasks that I already completed. Django provided me the perfect opportunity to implement this. Thanks to the learning and motivation provided by CS50 and its course which helped me excel and achieve this goal. It offered me tools and skills to resolve the logical complexity of implementing such features which requires some server managing these operations of storing tasks in database, user authentication and many more.

## Requirements
This project depends on Python3 as programming language, pip for installing tools and Django as web framework. So the requirements for this project are:
- Python3
- pip3
- Django==3.2

## File Structure
Some important Files and folders in this project are described as:
```
Tasks/
├── assets 									- Contains screenshots and logo for this README.md
├── manage.py
├── README.md 							- This README.md you are viewing
├── requirements.txt 				- Enlists the requirements of this project
├── tasks/ 									- Project Directory
│   ├── forms.py 						- Forms used in the app 
│   ├── migrations/					- Migrations created
│   │   └── migration files
│   ├── models.py 					- Models used in the app for storing tasks
│   ├── static/
│   │   ├── app.js 					- Main javascript file for app
│   │   └── assets 					- Favicons and logo used in the app
│   ├── templates/ 					- View's HTML template files
│   │   └── tasks/
│   │       ├── add.html 				- View for adding new tasks
│   │       ├── dashboard.html 	- View for dashboard
│   │       ├── edit.html 			- View for editing existing task
│   │       ├── index.html 			- View for landing page
│   │       ├── layout.html 		- View for layout which is inherited by all other views
│   │       ├── login.html 			- View for user login
│   │       ├── password.html 	- View for changing user's password
│   │       └── register.html 	- View for creating new users
│   ├── tests.py
│   ├── urls.py 						- All the registered routes for tasks app
│   └── views.py 						- Logic for routes and handling requests
└── todo
```

