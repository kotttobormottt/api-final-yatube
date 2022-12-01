# Проект API Yatube
Приложение к проекту YaTube https://github.com/kotttobormottt/YaTube Позволяет работать с YaTube через API:
```
запросы к API начинаются с /api/v1/
документация к API доступна по /redoc/
```

Проект выполнен в соответствии с документацией, доступной по ссылке: http://127.0.0.1:8000/redoc/


## Как запустить проект:
### Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/kotttobormottt/api_final_yatube.git
cd api_final_yatube
```
### Cоздать и активировать виртуальное окружение:
```
python3 -m venv env
source env/bin/activate
```
### Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```
### Выполнить миграции:
```
python3 manage.py migrate
```
### Запустить проект:
```
python3 manage.py runserver
```

### Примеры. Некоторые примеры запросов к API.

Запрос на получение постов:

```
http://127.0.0.1:8000/api/v1/posts/
```

Запрос на получение списка групп
```
http://127.0.0.1:8000/api/v1/groups/
```
