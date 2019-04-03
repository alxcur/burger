# Node Express Handlebars

### Overview
In this assignment, you'll create a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM (yum!). Be sure to follow the MVC design pattern; use Node and MySQL to query and route data in your app, and Handlebars to generate your HTML.

![alt text](https://raw.githubusercontent.com/alxcur/burger/master/Screen%20Shot%202019-04-01%20at%2010.58.09%20AM.png)

#### App Setup
1. Create a GitHub repo called `burger` and clone it to your computer.
2. Make a package.json file by running `npm init` from the command line.
3. Install the Express npm package: `npm install express`.
4. Create a server.js file.
5. Install the Handlebars npm package: `npm install express-handlebars`.
6. Install MySQL npm package: `npm install mysql`.
7. Require the following npm packages inside of the server.js file:
   * express

#### Directory structure
```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```

### Minimum Requirements

Attempt to complete homework assignment as described in instructions. If unable to complete certain portions, please pseudocode these portions to describe what remains to be completed. Hosting on Heroku and adding a README.md are required for this homework. In addition, add this homework to your portfolio, more information can be found below.
 
- - -

Alex Curington | SMU Coding Bootcamp | March 2019
