# Django-project

Install Django:
First, make sure you have Python installed. Then, install Django using pip:
-> pip install django 

Create a new Django project by running the following command:
-> django-admin startproject myproject
-> cd myproject


Next, create a Django app within the project:
-> python manage.py startapp myapp


Run the development server to test your application:
-> python manage.py runserver

Build and run the Docker container:
-> docker build -t my_django_app .
-> docker run -p 8000:8000 my_django_app
