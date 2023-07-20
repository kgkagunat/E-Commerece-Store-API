# E-Commerece-Store-API

## Overview

This application is a back-end system for an e-commerce website. 
It allows for the management of product inventory including products, categories, and tags. 
It is built with Node.js, Express.js, and Sequelize to interact with a MySQL database.

## Challenges and Acceptance Criteria

In this project, I was tasked with the challenge of setting up a back-end system for an e-commerce website, with full CRUD functionality for the product data. Here is the acceptance criteria:

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

## Key Features

- View all products, categories, or tags.
- Add new products, categories, or tags.
- Update existing products, categories, or tags.
- Delete products, categories, or tags.

## Usage

To use this application:

1) Clone the repository to your local machine.
2) Install necessary dependencies by running `npm install` in the command line.
3) Set up the database in MySQL using the `db/schema.sql`.
4) Seed the database with provided data by running `npm run seed`.
5) Start the server by running `npm start`.

## Installation

1) Clone the repository to your local machine.
2) Run `npm install` in the command line to install the necessary dependencies.
3) Make sure to have MySQL installed on your machine.
4) Run the `db/schema.sql` in MySQL Workbench to set up the database.
5) If you want to populate the database with test values, you can run `npm run seed` in the terminal.
6) Rename `.env.Example` to `.env` and modify the MySQL connection settings with your own credentials.

## Setting Up Your MySQL Connections

1) Open `.env` in your code editor.
2) Modify the `DB_USER` and `DB_PASSWORD` properties in the file to match your MySQL credentials.
3) Here's is what the .env file should look like:

```env
DB_NAME='ecommerce_db'
DB_USER='your_user_enter_here'
DB_PASSWORD='your_password_enter_here'
```
Replace "your_user_goes_here" and "your_password_goes_here" with your MySQL user, password, and host respectively.

## License

This project is licensed under the terms of the MIT license.

## Video Walkthrough Link

https://github.com/kgkagunat/E-Commerece-Store-API/assets/127634764/38553002-0c99-4aee-bf51-7f2b1dcb8265


