# nodejs-server
A sample Node.js app using Express 4

There are a few dependencies here, so let’s talk through what each of them does:

1. bcrypt-nodejs allows us to use a hashing algorithm to secure passwords stored in our database
2. body-parser is middleware for our express server, that allows us to parse request bodies
3. cors will deal with any Cross Origin Resource Sharing (CORS) issues we might run into
4. Express is of course the express server itself, which is a simple server framework for Node
5. jsonwebtoken allows us to create, sign, and read JSON Web Tokens
6. mongoose allows us to easily work with objects in our MongoDB database
7. morgan outputs some useful debugging information for us
9. passport is our authentication middleware
10. passport-jwt is one of Passport’s authentication “Strategies” which are like plugins
11. passport-local is another Passport Strategy, which uses simple username and password authentication

Before we Get Started

Before you go through this tutorial, you should have at least a basic understanding of Ionic 2 concepts. You must also already have Ionic 2 set up on your machine. You should also have a basic understanding of Node, Express, and MongoDB. For a basic introduction to NoSQL and MongoDB you can read An Introduction to NoSQL for HTML5 Mobile Developers. Node and Express are explained in a reasonable amount of detail in this tutorial, so additional reading may not be required.

1. Create the Folder and File Structure

We will be creating two different projects for this tutorial, one for our Ionic 2 front end (the client) and one for the Node backend (the server). This tutorial is going to focus on the server, and we aren’t going to use any tools to auto-generate the project for us like the Ionic CLI will do for our Ionic project, so we are just going to create the structure manually.

+ nodejs-server
  + app
    + controllers (authentication.js, todos.js)
    + models (todo.js, user.js)
    routes.js
  + config (auth.js, database.js, passport.js)
  package.json
  server.js


    
  

