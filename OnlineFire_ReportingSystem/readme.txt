https://www.askpython.com/django/django-commands

1. Create a Django project
If you are familiar with Django, you know that Django provides an initial collection of files, folders, and settings to start our project. To create the initial Django project structure, open your OS terminal and cd to the directory or folder where you want to keep your Django project code. Then run the following command on the chosen terminal which will create a directory/folder with the <project_name> provided in the command within the present working directory.

> django-admin startproject <project_name>

2. Make migrations command
> python manage.py makemigrations

3. Migrate Command
> python manage.py migrate


4. Collect static files
> python manage.py collectstatic 

5. Create a Django App
> python manage.py startapp <app_name>


6. Create a superusers
> python manage.py createsuperuser

7. Change the password
> python manage.py changepassword <username>

8. Run server
> python manage.py runserver 