# REST_API 

**Simple REST API built with Node.js and Express.js**

**ABOUT THE PROJECT**

This project is entirely made for studies propuses.  The main goal was to feel what's like to develop in node.js :) 
The API can add, get, update and delete users. Testet on Postman platform.

<h3>What have I learned?</h3>
<p>:pushpin: Understanding REST APIs and how to implement API and use HTTP methods</p>
<p>:pushpin: I have been familiar with Postman</p>
      
<h3>How to open a file? 👀 👀</h3>
Download Node.js from the official site  https://nodejs.org/en/ 
I installed nodemon as well to restart automatically the node application when file change, so you probably need to install it also. 

```
npm install -g nodemon
```

then run the following at the terminal:
````
npm start
````

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
    
