# flask-basic-CRUD
a basic flask application which performs CRUD operations
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