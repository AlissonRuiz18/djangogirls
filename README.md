pip install - r requirements.txt
django-admin.exe startproject mysite .
python manage.py migrate
python manage.py runserver
python manage.py startapp blog
python manage.py makemigrations blog
python manage.py migrate blog