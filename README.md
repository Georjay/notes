# notes
[![Python Version](https://img.shields.io/badge/python-3.9.6-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/django-3.2.5-brightgreen.svg)](https://djangoproject.com)

notes is a Web API built with Django REST framework.

## Running the Project Locally

First, clone the repository to your local machine:

CMD:

```bash
git clone https://github.com/Georjay/notes.git
```

Install the requirements (You can create a virtual environment before doing this):

```bash
pip install -r requirements.txt
```

Create the database:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8000**.
 

