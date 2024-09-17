# 📚 Сравнение производительности и удобства использования различных ORM (Object-Relational Mapping) библиотек: Django ORM, SQLAlchemy и Tortoise ORM

Это простые веб-приложения для создания и подсчёта изделий (к примеру, болтов, гаек и шайб) с использованием базы данных SQLite.

## 🚀 Установка приложений:

## Django_ORM

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/your-repo/Diplom_ChetinSergey.git
   ```

2. Перейдите в папку проекта, написав в консоли:
   ```bash
   cd Django_ORM
   ```

3. Установите необходимые бибилиотеки:
   ```bash
   pip install django
   pip install django-json-widget
   ```

4. Запустите приложение:
   ```bash
   py manage.py runserver
   ```

## SQLAlchemy_ORM

1. Используйте тот же репозиторий:

2. Перейдите в папку проекта, написав в консоли:
   ```bash
   cd SQLAlchemy_ORM
   ```

3. Установите необходимые бибилиотеки:
   ```bash
   pip install sqlalchemy
   pip install sqlalchemy-utils
   pip install fastapi
   pip install uvicorn
   ```

4. Запустите приложение:
   ```bash
   py -m app.main
   ```

## Tortoise_ORM

1. Используйте тот же репозиторий:

2. Перейдите в папку проекта, написав в консоли:
   ```bash
   cd Tortoise_ORM
   ```

3. Установите необходимые бибилиотеки:
   ```bash
   pip install tortoise
   pip install tortoise-orm
   ```

4. Запустите приложение:
   ```bash
   py -m app.main
   ```

## 💡 Использование

### 🔑 Аутентификация пользователя

## Django_ORM

Добавив в адресной строке `/admin` вы попадаете на страницу аутентификации:

```json
{
  "username": "admin",
  "password": "admin"
}
```

## SQLAlchemy_ORM и Tortoise_ORM

Добавив в адресной строке `/docs` вы попадаете на страницу Swagger:


### ➕ Добавление новых изделий, соединений и заказов

## Django_ORM

В соответсвующей строке нажмите "+ add" и вас перенаправит на страницу с формой создания изделия.
Аналогичным образом формируются соединения и заказы.
Также предусмотрены дополнительные инструменты для редактирования и удаления изделий.

## SQLAlchemy_ORM и Tortoise_ORM

Попадая в Swagger через различные "get, post, put, delete" - запросы можно соответственно запрашивать, создавать, изменять, удалять интересующие нас изделия.
Подобным же образом по определенным схемам формируются соединения и заказы.

👨‍💻 Спасибо за внимание!

