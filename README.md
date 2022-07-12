# Django REST Framework - [UserRegistration-Authentication]

Django app to register and authenticate user using REST API framework.

## How to use:
  - `pip install -r requirements.txt`
  - `python3 manage.py runserver`
  
## URLs to target:
  - to register a user
    - localhost:8000/api/addUser/
  - to login a user
    - localhost:8000/api/login/
  - to logout a user
    - localhost:8000/api/logout/

## Note: token is generated using uuid package.

## Useful commands:
  - `python3 manage.py createsuperuser`
  - `python3 manage.py makemigrations`
  - `python3 manage.py migrate`

# Note in my OS python2 and python3 both are installed that's why i have to mention python3