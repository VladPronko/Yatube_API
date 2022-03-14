# Проект «API для Yatube»
<a href='https://github.com/VladPronko/hw05_final'>Yatube</a> - социальная сеть для публикации личных дневников. В данном проекте реализована REST API для проекта Yatube.

К проекту по адресу http://127.0.0.1:8000/redoc/ подключена документация. В ней описаны возможные запросы к API и структура ожидаемых ответов. Для каждого запроса указаны уровни прав доступа: пользовательские роли, которым разрешён запрос.

Используемые технологии: Python3, Django 2.2, Django REST Framework, SQLite3, Simple-JWT.

# Как запустить проект:
- Клонировать репозиторий и перейти в него:
>git clone git@github.com:VladPronko/api_final_yatube.git

>cd api_final_yatube 

- Cоздать и активировать виртуальное окружение:
>python3 -m venv venv

>source venv/bin/activate

- Установить зависимости из файла requirements.txt:
>python3 -m pip install --upgrade pip

>pip install -r requirements.txt

- Выполнить миграции:
>cd yatube_api

>python3 manage.py migrate

- Запустить проект:
>python3 manage.py runserver
