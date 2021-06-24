![login](https://github.com/dg-veiga/todo-list-django/blob/master/img/login.JPG)

![list](https://github.com/dg-veiga/todo-list-django/blob/master/img/list.JPG)

![create-task](https://github.com/dg-veiga/todo-list-django/blob/master/img/task-create.JPG)

# To-do list application :pen:

Developed based on the tutorial made by [Dennis Ivy](https://github.com/divanov11).

Go to the [youtube tutorial video](https://www.youtube.com/watch?v=llbtoQTt4qw&t=2s) and check out.

## To make it work

Clone this repository

    $ git clone https://github.com/dg-veiga/todo-list-django

Go to the project folder

    $ cd todo-list-django

Assuming that you have Django installed, run the django server

    $ python manage.py runserver
    
## To create a super user and access the django admin panel

Be sure that you are inside the main folder and type 

    $ python manage.py createsuperuser

After that, insert the requested data to finish the register and run the server again if it's closed.
    
    $ python manage.py runserver
    
    # Go to the "localhost:8000/admin" and input your username and password. Voilá.
    # [More info](https://docs.djangoproject.com/en/3.2/intro/tutorial02/#introducing-the-django-admin).

