# MERN Real-Time Chat Application PART 2

* Open the `VSCode Terminal` and create a react app named `frontend`
*     npx create-react-app frontend
<br>

* Open another terminal and start the server
*     npm start
<br>

* Now open the `frontend` terminal and navigate to the `frontend` folder
*     cd frontend
*     npm start
* Remove unnecessary files and code from the `src` folder
<br>

* Install the `Chakra UI` in the `first terminal`
*     npm i @chakra-ui/react @emotion/react @emotion/styled framer-motion
* `Chakra UI` is something similar to `Bootstrap`
* Now go to `index.js` and wrap your application in the `ChakraProvider`
* ```
  <ChakraProvider>
      <App />
    </ChakraProvider>
  ```
*     import { ChakraProvider } from '@chakra-ui/react'
* Restart your `React app` and observe the changes
  

