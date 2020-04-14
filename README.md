# python_rest

1. `vagrant up`
1. `cd /vagrant/`

    Project workspace syncs in this directory
1. `python -m venv ~/env`

    Create a virtual env
1. `source ~/env//bin/activate`

    Activate it
1. `django-admin.py startproject profiles_project .`

    Creates the `profiles_project` project
1. `python manage.py startapp profiles_api`

    Creates the `startapp` app.
1. `python manage.py runserver 0.0.0.0:8000`

    Runs the server.
