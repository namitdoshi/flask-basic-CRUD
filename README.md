# Flask Crud App

A basic flask application which performs CRUD operations

## About Flask

Flask-MicroServices is a simple, lightweight attempt at bringing self contained module hierarchy to Flask. Better project organization through separation of concerns, isolating the different sections of your app into separate modules, or ‘microservices’.

An opinionated, but minimal approach to higher maintainability with Flask.

[Website](https://palletsprojects.com/p/flask/)

## Installation

clone this repository
```
[In]: git clone git@github.com:namitdoshi/flask-basic-CRUD.git
```
install dependencies:
```
[In]: pip install flask
[In]: pip install flask_sqlalchemy

```

## Use

### Run the application
move to app.py directory
```
flask run
```
This will open up a simple development HTTP server on localhost where you will be able to see functionality.


### App routes

**CREATE** and **READ** 

are HTTP **POST** or **GET** requests to the localhost.

**UPDATE** 
> /update/<ELEMENT_ID>

updates the element with an HTTP **POST** request

gets updates of the element with an HTTP **GET** request, after an update returns with OK (200)
 
**DELETE**
> /delete/<ELEMENT_ID>

HTTP **GET** request sent to the above path will delete the element specified with ELEMENT_ID

## Contributing


## License
