# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Table of Content

- [My Task](#my-task)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Mock-Up](#mock-up)
- [Installation](#installation)
- [Usage](#usage)
- [Skills Used](#skills-used)
- [Credits](#credits)

## My Task

1. Build the back end for an e-commerce site
2. Configure a working Express.js API
3. Use Sequelize to interact with MySQL database

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
```

## Mock-Up

Please find GIF of walk through below

![working example gif](./assets/Object%20Relational%20Mapping.gif)

Please find MP4 of walk through below

[click here for mp4](https://drive.google.com/file/d/1PyFQjxXppL-zDcxn1_LaYSURqwbmniJk/view)

## Installation

```
npm i
```

## Usage

To run this application follow the below:

1. Open the repository in your terminal or bash.
2. Log into MySQL in your command line
3. Create the Database SOURCE ./db/schema.sql
4. Quit MySWL
5. npm run seed
6. npm run watch
7. open up insomnia for testing

## Skills Used

• Sequelize

• Express.js

• inquirer

• MySQL

• API Routing

• Seed Data

• RESTful CRUD

## Credits

• [.env](https://www.npmjs.com/package/dotenv)

• [inquirer](https://www.npmjs.com/package/inquirer/v/8.2.4)

• [MySQL 2](https://www.npmjs.com/package/mysql2)

• [npm watch](https://www.npmjs.com/package/npm-watch)

• [npm run](https://www.npmjs.com/package/npm-run)
