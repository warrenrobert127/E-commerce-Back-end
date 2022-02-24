# E-commerce-Back-end

![Github licence](http://https://img.shields.io/badge/license-MIT-License-blue.svg)
  ## Description 
  This project is the back end for an e-commerce site. This application uses Express.js and Sequelize to interact with a MySQL database. This application creates a database using MySQL models and associations. API Routes are created to perform RESTful CRUD operations using sequelized models.
  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Tests](#tests)
  * [Questions](#questions)
  
  ## Installation 
 * Dependencies/Packages
    - Node.js
    - Express.js
    - MySQL2
    - Sequelize
    - dotenv

* Git clone the repo from Github

* Navigate to the folder and run `npm install` in your terminal.

* Be sure to include your MySQL user/password information in .env file.

* Database Connection
    - `mysql -u root -p`
    - `source schema.sql`
    - `npm run seed` [To seed the file]

* Run the app
     - `npm start` [To start the server] and navigate to <http://localhost:3001/> in your browser OR Use Insomnia Core
  ## Usage 
  1. Walkthrough video covers MySQL  [Click here](https://user-images.githubusercontent.com/20363030/155462730-36948796-0599-4e11-ae78-1770c68af974.mp4)<br>
    * Source the schema <br>
    * Seed the database <br>
    * Start the npm Server
       
2. Walkthrough video covers API routes being tested in Insomnia Core. [Click here](https://user-images.githubusercontent.com/20363030/155464743-812f5428-8f2b-4f04-a338-55f091616298.mp4)<br>
[click here](https://user-images.githubusercontent.com/20363030/155464913-cecfb376-a85c-4785-b018-a3aee1232566.mp4)
    *  GET routes for all categories, all products, and all tags. GET routes for a single category, a single product, and a single tag by Id. POST, PUT, and DELETE routes for categories, products, and tags. 
     

3. Walkthrough video showing all the technical acceptance criteria met. [Click here]<a href="src/E-commerce-Back-end-1645682637931.mp4"></a<br>
    * Uses the MySQL2 and Sequelize packages to connect to a MySQL database
    * Uses the dotenv package to use environment variables to store sensitive data, like a user’s MySQL username, password, and database name.
    * Syncs Sequelize models to a MySQL database on the server start.
    
    
  
  ## License
  MIT-License
  ## Tests
 There are no tests
  ## Questions
  If you have any questions about this projects, please contact me directly at warrenrobert127@gmail.com. You can view more of my projects at https://github.com/warrenrobert127/E-commerce-Back-end