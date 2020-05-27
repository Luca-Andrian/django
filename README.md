## How to use it

```bash
$ # Get the code
$ git clone https://github.com/app-generator/django-project.git
$ cd django-project
$
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv env
$ source env/bin/activate

$ # Create tables
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Start the application (development mode)
$ python manage.py runserver # default port 8000

$ # Access the web app in browser: http://127.0.0.1:8000/
```

> Note: To use the app, please access the registration page and **create a new user**. After authentication, the app will unlock the private pages.
