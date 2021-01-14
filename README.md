# E-commerce Back-End

## Description of the Application
This is an example back-end program designed to mimic the back-end for a potential e-commerce website.

<br/>

## Installation
To install necessary dependencies, run the following commands:

```
npm install express sequelize mysql2 dotenv

```
<br/>

## Getting Started
* The user should log into the MySQL Shell and run:
    ```
    source db/schema.sql
    ```
    * Note: This can also be done by running "npm start" in the command line, though database will still need to be seeded.
* The user will then seed the database from the command line:
    ```
    npm run seed
    ```
* The user will start the program with the following command in the command line:
    ```
    npm start
    ```

<br/>

## Application Features
* CRUD API routes are currently in place for the following:
  - Categories
  - Tags
  - Products
* Uses MySQL2 and Sequelize to connect to the MySQL database.
* Uses environmnet variables stored in a .env file for sensitive information.
  
<br/>

## Link to GitHub Repository
https://github.com/chriswein12/e-commerce-back-end

<br/>

## How the application works
Click on the following image for a walkthrough video on Youtube.

[![Link to Walkthrough Video](http://img.youtube.com/vi/MCrvzVk-ZYk/0.jpg)](https://youtu.be/MCrvzVk-ZYk "E-Commerce Back-End")

<br/>

## Credits

*Project completed by Chris Wein*