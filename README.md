<img width="1000" alt="Vidly Project" src="https://github.com/dineschandgr/ReactJS_Vidly_Application/blob/master/vidly.png">


Run the following commands to get started

#npm install

- to download all dependencies

#npm start

- to start the server


1. This ReactJS app uses Axios library to connect to the backend Node.js application using http
2. The Node.js application is connected to MongoDB which is running in my local
3. Start the MongoDB server and run seed.js file to seed data to the DB
4. Then run Node index.js to start Node.js server
5. The Node application issues JWT token to client and client stores the JWT in browser cache
6. Everytime the JWT is sent with the request
7. Once the user logs out, the JWT is cleared from the browser
