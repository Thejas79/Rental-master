Rental Master 🏠

A Django-based Rental Management System that allows users to register, login, browse rental properties, and manage profiles.

🚀 Features

User authentication (login/register)

Property listing & descriptions

Contact & profile pages

Static assets (CSS, images, templates)

SQLite3 database (default)

📂 Project Structure
Rental-master/
│── manage.py              # Django management script
│── db.sqlite3             # SQLite database
│── requirements.txt       # Dependencies
│── README.md              # Documentation
│── Guest/                 # Main Django app
│   ├── forms.py
│   ├── settings.py
│   ├── urls.py
│   ├── views.py
│   ├── templates/         # HTML templates
│   └── static/            # CSS, images, JS
│── images/                # Extra project images

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/yourusername/Rental-master.git
cd Rental-master


Create virtual environment

python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows


Install dependencies

pip install -r requirements.txt


Apply migrations

python manage.py migrate


Create superuser (admin)

python manage.py createsuperuser


Run the server

python manage.py runserver


Open in browser:
👉 http://127.0.0.1:8000

🌐 Deployment

Use Render.com / Railway / Heroku for Python hosting.

Not suitable for direct deployment on Vercel (Vercel is for frontend/static apps).
