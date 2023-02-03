# DjangoSaunaTest

страница админа: http://127.0.0.1:8000/admin/
логин/пароль - admin/admin
домашняя страница (видна только залогиненному пользователю): http://127.0.0.1:8000/home/
контакты: http://127.0.0.1:8000/contacts/

Для запуска на Mac вводим в терминал:
python3 -m venv venv
source venv/bin/activate
python3 -m pip install django
python3 manage.py runserver

Для запуска на Windows вводим в терминал:
python -m venv venv
venv\scripts\activate
python -m pip install django
python manage.py runserver   
