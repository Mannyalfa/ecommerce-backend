# E-commerce Back End 

## Table of Contents

1. [Description](#description)

2. [Languages/Applications](#languages-applications) 

3. [License](#license)

4. [Repository URL](#repository-url)

5. [Installation](#installation) 

6.[Images](#Images) 

7. [Test-Demo](#test-demo)

8. [Credits](#credits)

## Description

An e-commerce site back end taking a working Express.js API and configuring it to use
Sequelize to interact with a MySQL database

GIVEN a functional Express.js API

WHEN I add my database name, MySQL username, and MySQL password to an environment variable file

THEN I am able to connect to a database using Sequelize

WHEN I enter schema and seed commands

THEN a development database is created and is seeded with test data

WHEN I enter the command to invoke the application

THEN my server is started and the Sequelize models are synced to the MySQL database

WHEN I open API GET routes in Insomnia Core for categories, products, or tags

THEN the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia Core

THEN I am able to successfully create, update, and delete data in my database

## Languages/Applications

JavaScript, Node.js, Express.js, MYSQL2, Sequelize, Dotenv, Insomnia

## License
MIT [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Repository URL
https://github.com/Mannyalfa/ecommerce-backend

## Installation
After cloning the repository, execute the following commands:
	$ npm install
    	
        $ mysql -u root -p
    	
        mysql> (password)
    	
        mysql> use ecommerce_db
    	
        mysql> source db\schema.sql    
    	
        mysql> quit
    	
        $ npm run seed
    	
        $ node server.js

(See installation video under 'Test-Demo' below)


## Images
Initialize MySQL and source schema:
![screenshot](https://github.com/Mannyalfa/ecommerce-backend/blob/main/images/mysql-setup.jpg)

Seeding the database:
![screenshot](https://github.com/Mannyalfa/ecommerce-backend/blob/main/images/seed-database.jpg)

Starting the server:
![screenshot](https://github.com/Mannyalfa/ecommerce-backend/blob/main/images/start-server.jpg)

Ready to test routes
![screenshot](https://github.com/Mannyalfa/ecommerce-backend/blob/main/images/screenshot.jpg)

## Test-Demo
Installation:

https://drive.google.com/file/d/1ru0Wijqz7mDvnGuTjW4LjuN39rmaKFqn/view?usp=sharing

Technical Acceptance Criteria:

https://drive.google.com/file/d/1tJ4ij014nroNlHKwCZENvK62jMTQX8QN/view?usp=sharing

API Category/Product/Tag Routes Walkthrough with 'Insomnia':

https://drive.google.com/file/d/1fm5h5Yre5VbPUklEG1ePyJQVfy9Y3J58/view?usp=sharing
    

## Credits
Manny Alfaro

UCF-VIRT-BO-FSF-PT-04-2021-U-B


### If you have any questions, please contact me: mannyalfa@gmail.com