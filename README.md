# Weather-App
Django Weather Application
1. Set up a Django project:
   ```
   django-admin startproject <projectname>
   ```

2. Create a Django app within the project:
   ```
   python manage.py startapp weather
3.Create database tables for the models:
   Run the following command to create the necessary database tables for your models:
   ```
   1.python manage.py makemigrations
   2.python manage.py migrate

4.go to views.py
 -->url='http://api.openweathermap.org/data/2.5/weather?q={},&appid="yourapikey"&units=metric'
 -->change your api key
 -->go to this website 'api.openweathermap.org'
 -->get your api key and paste "url"

5.Run the development server:
    1.python manage.py runserver
 
