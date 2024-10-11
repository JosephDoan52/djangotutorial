# Django Tutorial
## Part 1
### Django version check 
```
python3 -m django --version
```
### Django - Creating a project
- Bootstrap a new Django project
```
mkdir djangotutorial
```
- Create a project called ***djangotutorial*** inside the ***djangotutorial*** directory.
```
django-admin startproject djangotutorial
```
### Django - Runserver
```
python manage.py runserver
```
### Django - Create app
```
python manage.py startapp <appname>
```
### Projects vs. apps
- What’s the difference between a project and an app? An app is a web application that does something – e.g., a blog system, a database of public records or a small poll app. A project is a collection of configuration and apps for a particular website. A project can contain multiple apps. An app can be in multiple projects.

