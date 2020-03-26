# book-app
[![Build Status](https://travis-ci.com/izola1/book-app.svg?branch=master)](https://travis-ci.com/izola1/book-app) [![Coverage Status](https://coveralls.io/repos/github/izola1/book-app/badge.svg?branch=master)](https://coveralls.io/github/izola1/book-app?branch=master) [![Maintainability](https://api.codeclimate.com/v1/badges/e6b1c88851e6fa2308d8/maintainability)](https://codeclimate.com/github/izola1/book-app/maintainability)

## Technologies Used

[node]: (https://nodejs.org)

- [Node.js](node)
- [postgreSQL](node)
- [Express.js](https://expressjs.com).
- [ESLint](https://eslint.org/).
- [Airbnb](https://www.npmjs.com/package/eslint-config-airbnb).

## Testing Tools

- [Mocha](https://mochajs.org/).
- [Chai](https://chaijs.com).

## Installations

#### Getting started

- You need to have Node and NPM installed on your computer.
- Installing [Node](node) automatically comes with npm.

#### Clone

- Clone this project to your local machine `git@github.com:victorsteven/Book-app-NodeJS-PostgreSQL-Travis-Coveralls-Code-Climate.git`

#### Setup

- Installing the project dependencies
  > Run the command below
  ```shell
  $ npm install
  ```
- Start your node server
  > run the command below
  ```shell
  $ npm run dev
  ```
- Use `http://localhost:8000` as base url for endpoints

## Rest API Endpoints

| METHOD | DESCRIPTION                             | ENDPOINTS                 |
| ------ | --------------------------------------- | ------------------------- |
| POST   | Add a book                              | `/api/v1/books`           |
| GET    | Get all the book                        | `/api/v1/books`           |
| PUT    | Update the details of a book            | `/api/v1/books/:bookId`   |
| GET    | Get a book particular book              | `/api/v1/books/:bookId`   |
| DELETE | Remove a book                           | `/api/v1/books/:bookId`   |


## Tests

- Run test for all endpoints
  > run the command below
  ```shell
  $ npm run test
