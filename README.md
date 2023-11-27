# ORM-E-Commerce-BackEnd

## Description
ORM-E-Commerce-BE is a backend application that providesdatabase creation with the options to add, delete, update data into the application via Insominia. This application utilizes dotenv, mysql2, sequalize, and express frameworks.

## Table of Contents
- [Overview](#overview)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Usage Instructions](usage-instructions)
- [Mock-Up](#mock-up)
- [GitHub URL](#github-url)
- [Walk-Through Video](#walk-through-video)

## Overview


## User Story
- AS A manager at an internet retail company
- I WANT a back end for my e-commerce website that uses the latest technologies
- SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia Core for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
- THEN I am able to successfully create, update, and delete data in my database

## Usage Instructions
1. First follow the githubrepository link below to access the application.
2. Clone the repo to your local machine using VS code of any other type of code editor.
3. Install the required dependencies to allow the application to function properly.
4. Log into your mysql account using terminal commands.
5. While still logged into mysql run "SOURCE db/schema.sql" to initialize your database.
6. Type quit into your command line to exit mysql.
7. Seed the database with the given seed file by typing "npm run seed" in the command line.
8. In the command line run " node server.js' to start your server on your local machine.
9. Pull up Insomnia and connect to your localhot server.
10. At this point a user can initiate GET, PUT, POST, and DELETE actions with the database as needed.


## Mock-Up
![Alt text](<media/Screenshot 2023-11-25 at 6.52.05 PM.png>)

![Alt text](<media/Screenshot 2023-11-25 at 6.52.32 PM.png>)

![Alt text](<media/Screenshot 2023-11-25 at 6.52.42 PM.png>)
## [GitHub URL](https://github.com/GrassHopper12345/ORM-E-Commerce-BE)


## [Walk-Through Video]()
