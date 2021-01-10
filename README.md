# E-Commerce-Backend

## Description

This is a back end for an e-commerce website that uses the latest technologies

## Table of Contents
* [Usage](#usage)
* [Technologies](#technologies)
* [WalkThrough Video](#walkthrough)
* [Contributing](#contributing)
* [Tests](#tests)
* [Questions](#questions)

## Usage

Initialize the database:
Use the schema.sql file in the db folder to create your database using MySQL shell commands.

        mysql -u root -p  <br db/schema.sql
        or 
        npm run db:init

        To Start the Server:
        npm start

## Technologies

We used Express.js API and configured it to use Sequelize to interact with a MySQL database.<br />
The dotenv package to use environment variables to store sensitive data. .env file is in the .gitignore file so its not uploaded to GitHub

### WalkThrough

This WalkThrough video shows the GET All, GET One, POST, PUT and DELETE API routes for Products, Tags and Categories. 

[Walkthrough (Part 1)](https://drive.google.com/file/d/1ZmcdnBOwq3AMP4ZnrArohC0yJnsu4OZA/view) - Initializing and seeding Database and Categories Routes<br />
[Walkthrough (Part 2)](https://drive.google.com/file/d/18duZ5bfZHJzeqTeiqywGD9iWdFwUURez/view) - Products and Tags Routes

## Contributing

Please contribute safely

## Tests

To seed the database for easy testing please run:

        npm run seed
    

## Questions
### Where is my GitHub repository for this project?
[GitHub](https://github.com/chattean/e-commerce-backend)

### How to get in Contact with me if you have additional questions?

anujchatterjee@gmail.com
    

