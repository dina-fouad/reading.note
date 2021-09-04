#  Django REST Framework & Docker

#### With Docker we now longer have to mess around with virtual environments. We can faithfully reproduce a production environment locally. And Docker can be shared among team members so everyone is working on the same setup. Wins all around.

### The important takeaways from this tutorial are this:

- Docker is a way to run Linux containers
- Containers are a lightweight alternative to Virtual Machines
- Dockerfile is a list of instructions for creating an image
- Images are made up of one or more layers
- Containers are a running instance of an image
- docker-compose.yml controls how to run the container
- Containers are stateless and ephemeral in nature. We can link the local filesystem via volumes but things become more complex with databases (which we didn’t cover here).

# Library Website and API

Django REST Framework works alongside the Django web framework to create web APIs. We cannot build a web API with only Django Rest Framework; it always must be added to a project after Django itself has been installed and configured.

### Traditional Django

- __init__.py is a Python way to treat a directory as a package; it is empty
asgi.py stands for Asynchronous Server Gateway Interface and is a new option in Django 3.0+
- settings.py contains all the configuration for our project
- urls.py controls the top-level URL routes
- wsgi.py stands for Web Server Gateway Interface and helps Django serve the eventual web pages
- manage.py executes various Django commands such as running the local web server or creating a new app.
- Run migrate to sync the database with Django’s default settings and start up the local Django web server.


### First app

Each app has a __init__.py file identifying it as a Python package. There are 6 new files created:

- admin.py is a configuration file for the built-in Django Admin app
- apps.py is a configuration file for the app itself
- the migrations/ directory stores migrations files for database changes
- models.py is where we define our database models
- tests.py is for our app-specific tests
- views.py is where we handle the request/response logic for our web app


