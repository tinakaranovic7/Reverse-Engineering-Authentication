# Reverse-Engineering-Authentication

Middleware- Doing authentication chech If the user isn't logged in, redirect them to the login page. 
config.json is the main configuration file. Data from config.json is used to configure the database. 
passport.js - Validates user name and password input. 
Models-represents shape of the data and business logic. 
login.js - Getting references to our form and inputs and validates each and every step. 
member.js- This file just does a GET request to figure out which user is logged in and updates the HTML on the page. 
signup.js - Doing multiple Validation and give ability to the user to sign up. 
Html files- Build the application UI structure for Log In, members and sign up page. 
Routes- is keeping API routing organized. 
package.json is a plain JSON(Java Script Object Notation) text file which contains all metadata information about Node JS Project or application. 
server.js- Is used to require necessary npm packeges, set up ports, create express app,configure middleware needed for authentication. Here we can sync our database and logging a message to the user upon success.

