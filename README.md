# MERN Real-Time Chat Application

* Open `VSCode` folder
*     npm init
*     npm i express
* Create a `backend` folder and a `server.js` file in it
<br>

* Start writing code in `server.js`
* ```
    const express = require('express')
    const app = express();
    app.listen(5000,console.log("Server started on PORT 5000"));
  ```
* To run the `server.js`, run the following command on terminal
*     node backend/server.js
* Add the following in the `scripts` section of the `package.json` created
*     "start":"node backend/server.js"
* Now, to run the server
*     npm start
<br>

* ```
  app.get('/',(req,res)=>{
    res.send("API is running");
  })
  ```
* Write the above in the `server.js` and start the server again.
* Visit `localhost:5000` in the web server and observe the output.
<br>

* Create a `data` folder with `data.js` file in the `backend` folder
* Add dummy data to the `data.js`
* Make necessary changes and additions in the `server.js` code
* Start the server again and observe the output at `localhost:5000/api/chat`
<br>

* Write the necessary endpoints and observe the api outcomes.
* Create a `.env` file in the `Project Folder` and install `dotenv` package
*     npm i dotenv
<br>

* To avoid restarting the server everytime we make changes : install `nodemon` package
*     npm i nodemon
* Make the following change in the `package.json`
*     "start": "nodemon backend/server.js"
* Now use `npm start` to start the server.
<br>

* Make sure you have a `POSTMAN` account and `POSTMAN Desktop Agent` downloaded in your system
* Test the `api endpoints` just created using POSTMAN.
<br>

*


