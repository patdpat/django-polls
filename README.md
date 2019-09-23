## django-polls

Sidtipat 6110546046

Created by
[Django Tutorial](https://docs.djangoproject.com/en/2.2/intro/)

## Requirements

The application requires

**Python** (v.3.6.6 or newer)

**Django** (v 2.2.5 or newer)

**Python Add-On Modules** on [requirements.txt](requirements.txt)

## Installation

**1. Install Python.**

-**Python** (v.3.6.6 or newer)

The official download site: https://www.python.org/downloads/

**2. To Run This Project**

Here's how to run for linux/ MacOS

For Window user go get Macintosh, or unix-like machine from your local computer store.

1.  Clone This Repository

        git clone https://github.com/patdpat/django-polls.git
        cd django-polls

2.  Install Requirements

        pip3 install -r requirements.txt

3.  Create **.env** file

        vi .env

    Learn Vim: https://scotch.iotutorials/getting-started-with-vim-an-interactive-guide

    Then add these to your **.env** file

        SECRET_KEY = 'whatever_string_you_want'
        DEBUG = True

4.  Migrate

        python3 mange.py migrate

5.  Run Server

        python3 manage.py runserver

6.  Redirect to the site from your favorite browser

        http://localhost:8000/
