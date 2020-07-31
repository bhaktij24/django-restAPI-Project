# django-restAPI-Project

This is a rest API based project through python django. The main idea of this project is based on reddit.com, where people can view different posts and vote for multiple posts. 
All the validations and authentications for each user are in place by making use of ValidationError library; generics, permissions, mixins, status libraries; Response library, from 
rest_framework.exceptions; rest_framework and rest_framework.response libraries respectively. Models defined here are Post and Vot, for which serialzers have also been created.

It runs on locahost, using the command python manage.py runserver. Once server is up and running, the urls that will work for this projects are:
1. localhost:8000/admin/
2. localhost:8000/api/posts
3. localhost:8000/api/posts/<id-of the-post>
4. localhost:8000/api/posts/<id-of the-post>/vote

Credentials for admin login are:
Username: bhaktijoshi
Password: abcd1234

However, you can create a new admin by giving the command python manage.py createsuperuser. The prompt will ask for username, password and emal. Enter the details and Bang on! 
You just created a new admin privileged user.
