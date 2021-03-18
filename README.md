# DEF Bank
> Banking Website built on Django
## Installation:
**1.Clone Repo**
```sh
https://github.com/sumitmallick/Banking-Management-System.git
```
**2.Setup Virtualenv & Install Requirements**
```sh
virtualenv env
source env/bin/activate
pip install -r requirements.txt
cd src
```
**3.Migrate Database**
```sh
python manage.py makemigrations
python manage.py migrate
```
**4.Create Superuser**
```sh
python manage.py createsuperuser
```
**5.Run Server**
```sh
python manage.py runserver
```

> while creating a new user it will generate a account number with which any user can login 


