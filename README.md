# yamdb_final for sprint16

![My workflow status](https://github.com/bimsuch/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg?event=push)

### Описание

Проект YaMDb собирает отзывы пользователей на различные произведения.


### Как запустить проект:

Клонировать репозиторий:

```
git clone git@github.com:DariaZhbanova/yamdb_final.git
```
Добавить следующие необходимые ключи (Secrets) в своем профиле GitHub по ссылке:
'https://github.com/<your_github_username>/yamdb_final/settings/secrets/actions'

1. Секретный ключ Вашего проекта для settings.py (установите свой, используя кавычки).  
SECRET_KEY = "some_funky_key"

2. Режим разработки или отладки (по умолчанию False).  
DEBUG = False

3. Параметр с указанием на используемый движок для доступа к базе данных.  
По умолчанию используется Postgres.  
DB_ENGINE = django.db.backends.postgresql

4. Имя базы данных.  
DB_NAME = postgres

5. Логин для подключения к базе данных.  
POSTGRES_USER = postgres

6. Пароль для подключения к базе данных (установите свой).  
POSTGRES_PASSWORD = "new_key"

7. Название сервиса (контейнера).  
DB_HOST = db

8. Порт для подключения к базе данных (принять как 5432).  
DB_PORT = 5432

Автор проекта:
```
Андрей
```