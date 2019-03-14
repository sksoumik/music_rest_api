# music_rest_api
A simple REST API for a list of songs built with Django REST framework. 

---
### Demo
![Alt Text](https://github.com/sksoumik/music_rest_api/blob/master/files/Screenshot%20(6).png)

---
### Set up, Test and Run

```
$ git clone git@github.com:sksoumik/music_rest_api.git
$ pip install requiremnets.txt
$ python manage.py makemigrations
$ python manage.py migrate
$ python manage.py test
$ python manage.py createsuperuser
$ python manage.py runserver
```
Go to ```127.0.0.1:8000/admin``` on your browser. Log in with your credentials while creating super user. Add few songs. 

Go to ```http://127.0.0.1:8000/api/v1/songs/``` for the output
