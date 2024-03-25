# Новостной портал

Cайт предназначен для сокращения адреса ссылки!

## Описание
Сайт создан с использованием микрофреймворка Flask в рамках обучения по программе Python Pro.

## Технологии
* Python
* Flask
* WTForms
* SQLAlchemy

## Как запустить

1. Склонируйте репозиторий
2. Создайте и активируйте виртаульное окружение
```commandline
python -m venv venv
source venv/Scripts/activate
```  
3. Установите зависимости
```commandline
pip install -r requirements.txt
```
4. Создайте файл .env и укажите настройки подключения к БД и другие параметры.
```commandline
DATABASE_URI=sqlite:///urls.db
SECRET_KEY=SECRET_KEY
```
5. Запустите flask приложение
```commandline
flask run
```

## Автор
Telegram:@Chertila046
