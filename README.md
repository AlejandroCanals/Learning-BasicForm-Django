# Form-Basic-Django

# JavaScript Integration Exercise with Django

In this repository, I have completed a hands-on exercise that demonstrates the integration of JavaScript with the Django web development framework. The exercise is based on content from a Coursera course on Full Stack web development from META, specifically week 3, titled "Fetching data using JavaScript".

#Objective of the Exercise:

The main objective of this exercise is to show how JavaScript can be used in conjunction with Django to process a form in a web application. 
It focuses on creating a basic form with the integration of JavaScript, Python(Django) and mySQL.

Through this exercise, I have learned how to effectively integrate JavaScript into a Django application to interact with the backend and frontend of a web application. I have also gained experience in handling forms, POST requests and manipulating JSON data in the context of web development.

This repository includes the complete source code of the exercise, which may be useful as a reference for future projects that require interaction between the frontend and backend in a Django application.

Feel free to explore the code and use it as a resource in your own web development projects!


**Technologies Used:** 

-Javascript

-Python

-Django

-MySQL



## Quick Start

Follow the steps below to set up the project:

### Prerequisites

- Ensure you have MySQL installed on your local machine and have set up the admin user.
- You will need Python and pipenv installed.

### Installation

1. Clone this repository to your local machine.

```bash
git clone https://github.com/iTzSRK/LittleLemon-BookingAPI.git
```

2. Navigate to the project directory:

```bash
cd LittleLemon-BookingAPI
```

3. Activate the virtual environment using pipenv:

```bash
pipenv shell
```

4. Install the required dependencies:

```bash
pipenv install django
pipenv install mysqlclient
```

### Database Setup

Before proceeding with migrations, make sure you have created the correct MySQL user, assigned privileges, and configured the database.

Create a .env file and fill it in with the credentials of your local database.

```dotenv
DEBUG=True
DB_NAME=reservations
DB_USER=    
DB_PASSWORD=
DB_HOST=127.0.0.1
DB_PORT=3306
```

Run the necessary commands to ensure the user can access the database.

### Run Migrations

Run the following commands to perform database migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

### Run the Development Server

Start the development server by running:

```bash
python manage.py runserver
```
