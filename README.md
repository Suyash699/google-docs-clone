Here is a google docs clone attempt.

Technologies used: 
  * Frontend: React, CSS
  * Backend: node.js
  * Database for retaining information: mongoose and mongoDB
  * Connection between frontend and backend: socket.io

  * This project was created as an attempt at learning socket.io, web socket and data transfer/ real time stateful data interchange between client and the server.
  * I learned that the web socket is a protocol, just like HTTP to establish a connection between the client and the server to exchange data.
  * HTTP uses a TCP protocol to establish a connection between the client and the server. It does so using a TCP handshake between the client and the server and by making use of a single channel system.
  * In this system, the information is carried by a single party at a time.
  * The websocket utilizes a dual channel system, where it makes use of the TCP handshake for the HTTP upgrade to websocket. The websocket then makes a two-way communication channel, which enables real time information being transmitted to other end.

  * To run the program:
		* cd to the /client folder and run the command "npm run start".
    * in another terminal, go to the /server folder and run "npm run devStart".
   
    * To see the effect of real-time data transfer, use the link of the react app in another browser with CORS plugin enabled.
