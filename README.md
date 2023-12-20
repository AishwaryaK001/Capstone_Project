Get Started With Django: Build a Hello World App
* Follow the instructions to build the app with Django.
* You can find the screenshots in the CapstoneProject_Documentation.doc

SETUP
=====
You can run the provided example project on your local machine by following the steps outlined below.

Create a new virtual environment:
$ python3 -m venv venv

Activate the virtual environment:
$ source venv/bin/activate

Install the dependencies for this project if you haven't installed them yet:
(venv) $ python -m pip install -r requirements.txt

Make and apply the migrations for the project to build your local database:
(venv) $ python manage.py makemigrations
(venv) $ python manage.py migrate

Run the Django development server:
(venv) $ python manage.py runserver

Navigate to http://localhost:8000/ or http://localhost:8000/projects to see project in action.