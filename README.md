## Django-rest-ifsc

A RESTful API written in Django to get any branch details using ifsc code and find all the branches of a bank in a Indian city.


### Setting up
This project was built with python +3.5

```bash
$ python3 -m venv env
$ env\Scripts\activate
$ pip install -r requirements.txt
$ cd django-rest-ifsc
$ python manage.py runserver
```

Then head to 

http://localhost:8000/api/ifsc/{ifsccode}

http://localhost:8000/api/branches/{city}/{bank-name}

in your browser to get started.

