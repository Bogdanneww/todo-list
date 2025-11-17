# Todo-list

A simple web application to manage your daily tasks.

## Installation

Make sure you have Python 3 installed on your system.

1. Clone the repository:
```bash
git clone https://github.com/Bogdanneww/todo-list.git


Create and activate a virtual environment:

python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate


Install project dependencies:

pip install -r requirements.txt


Create the database and apply migrations:

python manage.py migrate


(Optional) Create a superuser:

python manage.py createsuperuser


Start the development server:

python manage.py runserver


Open your browser and go to http://127.0.0.1:8000