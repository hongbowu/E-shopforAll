# E-shopforAll

E-shopforAll is an e-commerce back end application built using Express.js and Sequelize, designed to provide the latest technologies for managing an internet retail company's database.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Database Setup](#database-setup)
- [Starting the Application](#starting-the-application)
- [API Routes](#api-routes)
- [Testing](#testing)


## Installation

To install the necessary dependencies, run the following command:

npm install

## Usage

To use E-shopforAll, follow the steps outlined in the sections below. This includes setting up the database, starting the application, and testing the API routes.

## Database Setup

Create a .env file in the root directory.
Add your MySQL database name, username, and password to the .env file:
DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PW=your_mysql_password
Run the following commands to set up the development database and seed it with test data:
npm run schema
npm run seed

## Starting the Application

Run the following command to start the application:
npm start
This will start your server, sync the Sequelize models with the MySQL database, and make your API available.


## API Routes
Use a tool like Insomnia Core to test the following API routes:

Categories: /api/categories
Products: /api/products
Tags: /api/tags

Example
Use GET routes to retrieve data.
Use POST, PUT, and DELETE routes to create, update, and delete data.


## Testing
To test the API routes, make requests using Insomnia Core or any API testing tool.

## vedio link
https://watch.screencastify.com/v/CFkrDa4OV5cIR4SpvUbO


## Photos
![Alt text](<2024-01-10 002025.png>)
![Alt text](<2024-01-10 002035.png>)
![Alt text](<2024-01-10 002040.png>)
![Alt text](<2024-01-10 002045.png>)
![Alt text](<2024-01-10 002050.png>)
![Alt text](<2024-01-10 002056.png>)