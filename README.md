# BookBrowse
this is a book search engine


This is an application designed for the user to be able to search a book based on the apollo express server. 

Develop > 


# client >
 ## > node - module packages
 ## > public - standard react public import folder
# > src -
 ## > components
    > LoginForm.js - renders user information to the document and takes user login input 
    > Navbar.js - 
    > SignupForm.js - 
 ## > pages
    > user-controller - 

# server > 
 ## > config
    > connection.js - 

 ## > controllers
    > user-controller - 

 ## > models
    > index.js - 
    > Book.js - 
    > User.js - 

 ## > routes
    > index.js - 
    > api - 

 ## > schemas
    > index.js - 
    > resolvers.js - 
    > typeDefs.js - 

 ## > utils 
    > auth.js - 

 ## > package.json (inside of server)
 ## > server.js 

 ```
 const express = require('express');
const { ApolloServer, gql } = require('apollo-server-express');
const path = require('path');
const db = require('./config/connection');
const { typeDefs, resolvers } = require('./schemas');

 ```


 ## > package.json (inside of root folder)
