# node-aop-poc

This project is to test the aspect orientated paradigm using javascript. 

Before running the application, run an `npm install` to install your needed packages. 
You will need to make sure you have `concurrently` installed globally on your system. (`npm install -g concurrently`)

To run: 
`npm start` 

What this will do: 
This wil start up two web servers, a client and sink. The purpose of this project is to have the client's http call intercepted without clogging up the code. It should provide a start time and end time to the sink web server, which the sink will simply log. 
