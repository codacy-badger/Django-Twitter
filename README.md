# Django-Twitter
[![Heroku](https://heroku-badge.herokuapp.com/?app=ghoschts-django-twitter)](https://ghoschts-django-twitter.herokuapp.com/)
[![Django CI](https://github.com/GHOSCHT/Django-Twitter/workflows/Django%20CI/badge.svg)](https://github.com/GHOSCHT/Django-Twitter/actions?query=workflow%3A%22Django+CI%22)
[![CodeFactor](https://www.codefactor.io/repository/github/ghoscht/django-twitter/badge)](https://www.codefactor.io/repository/github/ghoscht/django-twitter)
[![License: WTFPL](https://img.shields.io/badge/License-WTFPL-brightgreen.svg)](http://www.wtfpl.net/about/)

# Installation
- ``pipenv install`` to instal all required modules
- ``py manage.py collectstatic`` to collect all static files
- Set environment variables
### Enviornment variables
- **consumer_key**, **consumer_secret**, **access_token**, **access_token_secret** for Twitter API authentication
- **secret_key**
- **HEROKU_DEPLOY** when deployed on heroku (value isn't important)
