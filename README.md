Todo-list 📝

A simple and intuitive web app to organize your daily tasks and stay on top of your schedule.

🚀 Quick Start

Clone the repository

git clone https://github.com/AnnaLub/todo-list
cd todo-list


Create and activate a virtual environment

python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate


Install dependencies

pip install -r requirements.txt


Apply database migrations

python manage.py migrate


(Optional) Create a superuser for admin access

python manage.py createsuperuser


Start the development server

python manage.py runserver


Open http://127.0.0.1:8000
 in your browser.

✨ Features

✅ View all tasks sorted by status (not done → done) and creation date

➕ Add new tasks with optional deadlines

✏️ Update or delete existing tasks

✔️ Mark tasks as Complete or Undo

🏷️ Assign multiple tags to tasks for better organization

🗂️ Create, edit, and delete tags

📸 Screenshots

Home Page / Task List


Add / Update Task Form


Tag List Page


You can put screenshots in a screenshots/ folder in your repo.

🛠 Technologies Used

Python 3

Django Framework

HTML5 & CSS3

Bootstrap 5
