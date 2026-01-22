# Notely App

Notely is a Django-based web application, designed for managing personal notes with a focus on organization, searchability, and a clean user experience.

## Features

- Categorize your notes using custom-colored badges.
- Quickly filter through your notes by searching for keywords in the title, content, or specific tags.
- Built with Bootstrap 5, featuring card hover animations, smooth transitions, and a simple mobile-friendly layout.
- Full user registration and loging system.
- Built-in API endpoints for future integration with mobile or desktop apps.

## Tech Stack

- Python
- Django Rest Framewrok
- Bootstrap
- HTML
- CSS
- 
## Instructions to setup

1. Clone the repository:
2. ```bash
3. git clone https://github.com/ivailoiliev89-netizen/Simple-Notely-app.git
4. pip install -r requirements.txt
5. python manage.py migrate
6. python manage.py createsuperuser
7. python manage.py runserver

## How to Use

1. Sign Up : Create a new account to start your collection.
2. Create Tags : Log into the Admin panel (/admin) to define your own categories ( Name: "Fishing", Color: "Blue").
3. Write Notes : Use the "New Note" button to save your thoughts and check the tags you want to apply.
4. Organize : Click on any tag on your dashboard to instantly filter notes by that category.
