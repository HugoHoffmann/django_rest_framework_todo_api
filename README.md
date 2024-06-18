# Django Rest Framework Todo Api (Sqlite)

This project uses Django Rest Framework to create a Rest api with all the CRUD operations of a todo list. 

## To execute the project: 
** You can use a virtual environment to keep the dependencies locally
1. ```pip install -r requirements.txt```
2. ```python manage.py makemigrations```
3. ```python manage.py migrate```
4. ```python manage.py createsuperuser```
5. ```python manage.py runserver```
6. Login: http://localhost:8080/admin use the same user and password used on step 4
7. Access on browser: http://localhost:8080/todos/api to create and get the list of Todos
6. Access on browser: http://localhost:8080/todos/api/:id (with some integer id) to Update, delete and get detail of a specific todo record.