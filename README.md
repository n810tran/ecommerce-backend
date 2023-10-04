# E-Commerce Backend

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

A mysql database and application backend for an e-commerce site. 

## User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
  
## Acceptance Criteria
  
``` 
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
```
## Installation
After cloning repository, run

`npm install`

Use the following commands.

`mysql -u root -p`

"your password"

`source db/schema.sql`

`quit`

`npm run seed`

`npm start`

## Usage

Below are gifs showing the functionality of the application:

![Command Line start](./assets/CL%20GIF.gif)

![Categories](./assets/Categories%20Gif.gif)

![Products](./assets/Products%20Gif.gif)

![Tags](./assets/Tags%20GIf.gif)

## License
This application is licensed under the [MIT](https://opensource.org/licenses/MIT) license.

## Tests
No tests

## Questions
If you have any questions, you can reach me at [GitHub](https://github.com/n810tran) or by email at nathaniel.k.tran@gmail.com.