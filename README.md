Angular RESTful Service Example
This project provides a simple look at getting started using Angular to call into a RESTful service. Simply clone the project or download and extract the .zip to get started.

Angular Concepts Covered
Using TypeScript classes and modules
Modules are loaded with System.js
Using Custom Components
Using the Http object for Ajax calls along with RxJS observables
Performing GET and PUT requests to the server
Working with Angular service classes for Ajax calls
Using Angular databinding and built-in directives
Software Requirements To Run Locally (there's a Docker option below as well)
Node.js 4.0.0 or higher
MongoDB 3.2 or higher
Running the Application Locally
Install Node.js and MongoDB on your dev box

Execute 'mongod' to start the MongoDB daemon if it's not already running

Install Nodemon: npm install nodemon -g

Open config/config.development.json and change the host from mongodb to localhost

Run npm install to install app dependencies

Run npm start to compile the TypeScript and start the server

Browse to http://localhost:3000

Running the Application with Docker
Install Docker for Mac/Windows or Docker Toolbox - https://www.docker.com/products/overview

Open a command prompt window

Run npm install

Run npm run tsc:w to compile TypeScript to JavaScript locally (leave the window running). This is only needed when in "dev" mode.

Open another command window and navigate to this application's root folder in the command window

Run docker-compose build to build the images

Run docker-compose up to run the containers

Navigate to http://localhost:3000 if using Docker for Mac/Windows or http://192.168.99.100:3000 if using Docker Toolbox in a browser

Live long and prosper