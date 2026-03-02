This simple Django web application allows users to create topics and log entries for each one. 
It was built for learning and practice purposes and uses Django fundamentals such as views, models, templates and CRUD operations. 

Tech Stack used: Python 3

Django

SQLite

HTML / Django Templates


Features:

Create new topics

Add entries under topics

View list of topics

Edit existing entries

Clean project structure following Django best practices

Project Structure: learning_logs/
│
├── learning_logs/     # Main app
├── ll_project/        # Django project settings
├── manage.py
└── .gitignore

How to run locally: 

1. Clone the repository

    git clone https://github.com/sameen-sz/learning_logs.git
    cd learning_logs

2. Create and activate virtual environment

    python -m venv ll_env
    source ll_env/bin/activate   # Mac/Linux

3. Install dependencies

    pip install django

4. Run Migrations

    python manage.py migrate

5. Start the development server 

    python manage.py runserver

Visit: http://127.0.0.1:8000/

What I learned:

Migrations and Models 
Template rendering
URL routing
CRUD functionality 
Django project/app structure 
Git and Github workflow 

Future Improvements:

Add user authentication

Deploy to Render or Heroku 

Enhance UI styling

Add search functionality

Author: Sameen Shahbaz
GitHub: https://github.com/sameen-sz
