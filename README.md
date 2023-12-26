# Developing a Blog Website with Django
[![Image of my-views-counter](https://github.com/Faishal003/my-views-counter/blob/master/svg/731950256/badge.svg)](https://github.com/Faishal003/my-views-counter/blob/master/readme/731950256/week.md) ![Static Badge](https://img.shields.io/badge/python-3.10-blue?link=https%3A%2F%2Fwww.python.org%2Fdownloads%2Frelease%2Fpython-3100%2F) ![Static Badge](https://img.shields.io/badge/django-5.0-orange)
# Features of this project💥
* The user can log in and log out 🔐
* The user can access his profile and change the profile info 💁
* The user can also add & change his profile picture 💁
* The user can write & edit his blog ✍
* The user can like or dislike the post 👌
* Also the user can comment on a particular blog ✏️
# Installation
**Note :** Make sure you have Python version 3.10.10 👈<br>
Install a few prerequisite files before running the project 👀<br>
```
pip install django
pip install pillow
pip install Django-crispy-forms
pip install crispy-bootstrap4  
pip install django_cleanup 
```
# Clone the Repository
After installing the prerequisite files just clone the project:<br>
```
git clone https://github.com/Faishal003/Developing-a-Blog-Website-with-Django.git
```
# Create Superuser
Run command in terminal:
```
python manage.py createsuperuser
```
# Model Build
After creating `superuser`, run the following commands in the Terminal:
```
python manage.py makemigrations
python manage.py migrate
python manage.py makemigrations
```
# Getting started to run the server
Run command in terminal:<br>
Execute: `python manage.py runserver`<br>
Open up a browser and visit: <span style="color: blue;">http://127.0.0.1:8000/</span> , the you will see the blog💥❤️.<br>
All Set! 🤩🔥
