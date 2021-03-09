# LocationSearchByFlickerAPI
search locations using flicker api

## Python version

    python 3.8.8

## Django version

    Django==3.1.1

## Database

    sqlite3

## Other Packages

    flickrapi==2.4.0

# Commands to Execute before accessing

### Install all the dependencies required to run the project

    pip install -r requirements.txt

### To generate desired migrations files of created folder

    python manage.py makemigrations

### To apply generated migration to DB

    python manage.py migrate 

### Create user to perform search

    python manage.py createsuperuser
    
    Example Users: 
    1) Client
     email: dummy@geo.com ,  password: @1234567abc
	2) Admin
	 username: super
	 email: super@geo.com
	password: @1234567abc
	
## References:-

    https://www.flickr.com/services/api/flickr.photos.search.html
    https://pypi.org/project/reverse_geocoder/
    
    
## Live Demo:-
    https://geoappup.herokuapp.com/