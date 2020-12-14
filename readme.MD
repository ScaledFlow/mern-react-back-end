npm init
npm install express --save
npm install body-parser --save
npm install nodemon --save-dev
npm install uuid --save
npm install express-validator --save
npm install axios --save

npm install mongoose --save

GOOGLE API - google geocoding api
https://developers.google.com/maps/documentation/geocoding/overview


const {v4 : uuidv4} = require('uuid');
    
id: uuidv4(),


"start: 'nodemon app.js"


http://localhost:5000/api/places/p1

http://localhost:5000/api/places/user/u1

Postman - body raw json

ROUTES FOR PLACES

GET
http://localhost:5000/api/places/user/u2

http://localhost:5000/api/places/p1


POST
http://localhost:5000/api/places

{
    "title": "New York Stock Exchange",
    "description": "Where the money lives",
    "creator": "u2",
    "address": "11 Wall St, New York, NY 10005",
    "coordinates": {
        "lat": 40.7063069, 
        "lng": -70.010329
    }
}

PATCH
http://localhost:5000/api/places/p1
{
    "title": "New York Stock Crime Syndicate"
}

DELETE
http://localhost:5000/api/places/p1


ROUTES FOR USERS

GET
http://localhost:5000/api/users

POST - Create User
http://localhost:5000/api/users/signup

{
  "name": "Test Name",
  "email": "test2@test.com",
  "password": "testing" 
}

POST - Login
http://localhost:5000/api/users/login

{
  "email": "test2@test.com",
  "password": "testing" 
}

AFTER INSTALL OF AXIOS

POST
http://localhost:5000/api/places

{
    "title": "New York Stock Exchange",
    "description": "Where the money lives",
    "creator": "u2",
    "address": "11 Wall St, New York, NY 10005"
}