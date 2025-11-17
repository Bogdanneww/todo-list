Todo-list

A simple web application to manage your daily tasks efficiently.

Demo

Home Page


Tag List Page


Add / Update Task Page


Installation

Make sure Python 3 is installed on your system.

Clone the repository:
git clone https://github.com/Bogdanneww/todo-list.git

Create and activate a virtual environment:
Windows: .venv\Scripts\activate
macOS/Linux: source .venv/bin/activate

Install dependencies:
pip install -r requirements.txt

Apply migrations:
python manage.py migrate

(Optional) Create a superuser:
python manage.py createsuperuser

Start the server:
python manage.py runserver

Open your browser and go to http://127.0.0.1:8000

Features

View your task list, ordered by status and creation date

Add, update, or delete tasks

Categorize tasks with tags

Mark tasks as Complete or Undo

Sidebar navigation for easy access to Home and Tag pages

Project Structure

tasks/models.py – Task and Tag models

tasks/views.py – CRUD views and status toggle logic

tasks/templates/ – HTML templates for all pages

tasks/forms.py – Django forms for tasks

Technologies Used

Python 3

Django

HTML / CSS

Bootstrap 5

Django Crispy Forms
