# SocialLogins_Django-AllAuth

This app is built for testing Django AllAuth

This app supports login using facebook and google accounts currently

The official documentation of all auth is at https://django-allauth.readthedocs.io/en/latest/index.html

# How To Run App

Install all dependencies/packages using command "pip install -r requirements.txt"

Add google and facebook apps by providing client id and secret in settings.py file under 'SOCIALACCOUNT_PROVIDERS' 

You can also do this by adding google and facebook apps by logging into '/admin' and then clicking on social applications and add social application

For logging into '/admin' you need to create a super user using command 'python manage.py createsuperuser'

You can test app by running server using command 'python manage.py runserver'

your site will be at "http://localhost:8000"


