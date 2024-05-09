# MERN Real-Time Chat Application

* Open `VSCode` folder
*     npm init
*     npm i express
* Create a `backend` folder and a `server.js` file in it
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
