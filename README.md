# This is the Test project for Pratham software

This application is the test assignment which is created using nodejs, postgres database and sequelize Orm and React Js.
This project gets the data of user and after that let that user create, update and delete the tasks.

## Installation Requirements

To run back-end Just NPM Install and then NPM Start in root directory.

To run front-end cd frontend and then NPM Install and Then NPM Start

## Available Scripts

In the project directory, you can run:

### `npm install`

Install the required dependencies

### `npm start` backend

Runs the app in the development mode.\
the server starts at [http://localhost:8080].

### `npm start` frontend

Runs the app in the development mode.\
the server starts at [http://localhost:3000] [https://pratham-test.herokuapp.com].

## About the project

In this node application we used sequelize ORM to connect with postgres database.
We created the schema in models folder. The schema will be auto generated when you run npm start.
We have User controller to insert the data of user in user table.
We have task controller to create, update, delete and get the tasks.

Frontend is developed using react js using most popular libraries like redux, redux-thunk, redux-toolkit, react-bootstrap etc.


## libraries used in the Project

1. pg for Postgresql database
2. pg-hstore for connecting with Sequelize ORM
3. sequelize for ORM
4. swagger-ui-express for api-documentation

## Api documentation

For api documentation we used swagger-ui-express that is available on [http://localhost:8080/api-docs] [https://psi-test-backend.herokuapp.com/api-docs/]