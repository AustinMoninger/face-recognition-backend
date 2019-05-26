
# Face Recognition Web App Backend

This project is deployed with Heroku at this [link](https://frontend-face-recognition.herokuapp.com/).

This is a web application that allows users to provide links of images
and then, using the [Clarifai Face Recognition API](https://clarifai.com/models/face-detection-image-recognition-model-a403429f2ddf4b49b307e318f00e528b-detection),
the application visually indicates where the faces in the image are located. The front end code can be found at [this repo](https://github.com/AustinMoninger/face-recognition).

The backend server was created using Node.js and Express.js. The server is connected to a PostgreSQL database where user login information and the number of images they have submitted is stored.

## What I Learned

How to...

* create endpoints for a RESTful API
* create a backend server with Node.js and Express.js
* use Postman to test the endpoints of my server
* connect a backend server to a database and interacting with that database from the endpoints
* use a cryptographic library ([bcrypt](https://www.npmjs.com/package/bcrypt)) to store private user information in a database
* deploy a project with Heroku

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the backend in the development mode. This will probably not work in its current state because there are environment variables that depend on the Heroku environment that the project is deployed on.


