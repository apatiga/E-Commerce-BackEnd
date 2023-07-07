# Object Relational Mapping ORM: E-Commerce Back ENd Project

## Description

The MySQL database is connected to using Sequelize and the Express.js API by the back-end database for e-commerce websites. Users can construct a development database, populate it with test data, and sync Sequelize models to a MySQL database using the back-end database. Users can display and modify data in the users database by using the GET, POST, PUT, and DELETE routes. 

## The Challenge 

The task is to build the back end for an e-commerce site by modifying starter code. You’ll configure a working Express.js API to use Sequelize to interact with a MySQL database.


## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

## GIFS:

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)


## Usage Instructions

HAS ERRORS WILL BE GOING BACK TO FIX THE APPLICATION

    1. Repository: Open documentation run 'npm i' and update '.env'.
    2. Create database: use the schema.sql file in the db folder with MySQL shell commands. Use environment variables to store sensitive data like your MySQL username, password, and database name.
    3. Run 'npm run seed' to seed the database with test data. Then, run 'npm start' to start the server and sync the Sequelize models to the MySQL database.
    4. Generate a development database with test data, use the schema and seed commands.
    5. Use Insomnia to test http://localhost:3001 with the following route end points API GET, POST, PUT, and DELETE routes for categories, products, and tags, ensuring successful creation, updating, and deletion of data in the database. (Currently not able to create or delete)

## Built With 
* JSON
* Dotenv: 8.2.0
* Express: 4.17.1
* Node.js
* Express.js
* Node MySQL2: 2.1.0
* Sequelize: 6.32.1
* Insomnia: by Kong
* VScode

## Video Walkthrough

https://drive.google.com/file/d/1MdSwvIPmakvC-k9Zb0DE6sIZknfd5gvg/view







