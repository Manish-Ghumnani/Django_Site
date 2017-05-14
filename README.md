
Django:
install pip: python get-pip.py
install django pip install django

Starting a project:
1. django-admin startproject mysite
2. cd mysite
3. python manage.py runserver  (will create server at localhost)
4. python manage.py startapp app_name 
5. create view in views.py
6. add url in urls.py for your app and then route it to your app in urls.py in mysite
7. python manage.py migrate (initialise db)
8. include your apps config in Installed_apps tupple in settings.py
9. create models in models.py and then python manage.py makemigrations polls (add your models to migration)
10. python manage.py sqlmigrate polls 0001 (check what is your model's migration is and its sql)
11. python manage.py migrate (migrate the models you created)# Django_Site
