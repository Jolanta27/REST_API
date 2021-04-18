# REST_API 

Simple REST API built with Node.js and Express.js

ABOUT THE PROJECT

This project is entirely made for studies propuses.  The main goal was to feel what's like to develop in node.js :) 
The API can add, get, update and delete users. Testet on Postman platform.

How To Run

Download Node.js from the official site  https://nodejs.org/en/ 
I installed nodemon as well to restart automatically the node application when file change, so you probably need to install it also. 
npm install -g nodemon

the run the following at the terminal:
npm start

Endpoints:

      /users/ :

      Method: POST
      Description: Create a new user.
      Body: firstname, lastname, age
      
      Method: GET
      Description: Return a user data.

      Method: UPDATE
      Description: Update the user's fields.
      Body: firstname, lastname, age
      
      Method: DELETE
      Description: Delete a given user.
    
