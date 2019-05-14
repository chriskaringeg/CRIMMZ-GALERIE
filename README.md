# CRIMMZ-GALERIE

## Author

 KARINGE KINYUA

## Description

  A personal gallery application that I display photos for others to see.

## User Stories 

- View different photos that interest me.
- Click on a single photo to expand it and also view the details of the photo. The photo details must appear on a modal within the same route as the main page.
- Search for different categories of photos. 
- Copy a link to the photo to share with my friends.
- View photos based on the location they were taken.


## Tech used

- HTML and CSS
- Python
- Django
- Postgres
- Heroku for deployment
- Set up and Installation

## Prerequisites

The user will require git, django, postgres and python3.6+ installed in their machine. To install these two, you can use the following commands

#git
$ sudo apt install git-all

#python3.6
$ sudo apt-get install python3.6.

#django
$ pip install django==1.11

#postgres
$ sudo apt-get install postgresql postgresql-contrib libpq-dev

## Requirements
- config==0.4.0
- dj-database-url==0.5.0
- Django==1.11
- django-bootstrap3==11.0.0
- django-bootstrap4==0.0.7
- django-heroku==0.3.1
- gunicorn==19.9.0
- Jinja2==2.10
- MarkupSafe==1.1.0
- Pillow==5.3.0
- psycopg2==2.7.6.1
- python-decouple==3.1
- pytz==2018.7
- .ENV file
- SECRET_KEY='<SECRET_KEY>'
- DEBUG=True #set to false in production
- DB_NAME='galerie'
- DB_USER='user'
- DB_PASSWORD='password'
- DB_HOST='127.0.0.1'
- MODE='dev' #set to 'prod' in production
- ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
- DISABLE_COLLECTSTATIC=1 

## Installation
- To access this application on your command line, you need to clone it git clone https://github.com/chriskaringeg/CRIMMZ-GALERIE.git
- Create a requirements.txt in the root folder and copy the requirements above.
- Install the required technologies with pip install -r requirements.txt
- Create a .env file and copy the .env code above
- You can then run the server with: python3.6 manage.py runserver
- You can make changes to the db with python3.6 manage.py makemigrations photos python3.6 manage.py migrate
- You can run tests: python3.6 manage.py test photos

## Django Admin

Username: chris , Password: <private>

## Known Bugs x
Currently, there are no known bugs

## Live link
You can view the live site here

## License
This project is under the MIT licence

Copyright (c) 2019 KARINGE KINYUA