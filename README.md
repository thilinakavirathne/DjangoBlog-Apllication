# DjangoBlog


## Setup

Create a new virtual environment:

```bash
 python3 -m venv venv
```

Activate the virtual environment:

```bash
 source venv/bin/activate
```

Install the dependencies for this project if you haven't installed them yet:

```bash
 python -m pip install -r requirements.txt
```

Make and apply the migrations for the project to build your local database:

```bash
 python manage.py makemigrations
  python manage.py migrate
```

Run the Django development server:

```bash
python manage.py runserver
```
## Using the Django Admin site

To create new posts, you need to create a superuser:

```bash
 python manage.py createsuperuser
Username (leave blank to use 'root'): admin
Email address: admin@example.com
Password: RealPyth0n
Password (again): RealPyth0n
Superuser created successfully.
```

When running the `createsuperuser` managemant command you're prompted to choose a username, provide an email address, and set a password. Use your own data for these fields and make sure to remember them.

Navigate to `http://localhost:8000/admin` and log in with the credentials you just used to create a superuser. 
