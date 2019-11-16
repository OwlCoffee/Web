# Usage
Clone this repo, setup virtualenv, install Django
```
git clone https://github.com/OwlCoffee/Web
cd django-calendar

python -m venv venv
pip3 install django

python3 manage.py migrate
python3 manage.py runserver
```
Find the app running at http://localhost:8000/calendar/