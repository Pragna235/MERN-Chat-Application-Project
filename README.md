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


