# book-app
[![Build Status](https://travis-ci.com/izola1/book-app.svg?branch=master)](https://travis-ci.com/izola1/book-app) [![Coverage Status](https://coveralls.io/repos/github/izola1/book-app/badge.svg?branch=master)](https://coveralls.io/github/izola1/book-app?branch=master) [![Maintainability](https://api.codeclimate.com/v1/badges/e6b1c88851e6fa2308d8/maintainability)](https://codeclimate.com/github/izola1/book-app/maintainability)

## Project Technologies
   Below are the technologies used for the project:
[node]: (https://nodejs.org)

- [Node.js](node)
- [postgreSQL](node)
- [Express.js](https://expressjs.com).
- [ESLint](https://eslint.org/).
- [Airbnb](https://www.npmjs.com/package/eslint-config-airbnb).

## Project Testing Tools
   The following Testing frameworks/libraries were used:
- [Mocha](https://mochajs.org/).
- [Chai](https://chaijs.com).

## Installations

#### Project Requirements

- You need to have Node and NPM installed on your computer.
- Installing [Node](node) automatically comes with npm.

#### Project Cloning

- You can clone this project to your local machine `https://github.com/izola1/book-app.git`

#### Setup

- Installing the project dependencies
  > Run the command below
  ```shell
  $ npm install
  ```
- To start your node server
  > run the command below
  ```shell
  $ npm run dev
  ```
- `http://localhost:7000` is the base url for the endpoints

## Rest API Endpoints

| METHOD | DESCRIPTION                             | ENDPOINTS                 |
| ------ | --------------------------------------- | ------------------------- |
| POST   | To add a book                           | `/api/v1/books`           |
| GET    | To get details of all books             | `/api/v1/books`           |
| PUT    | To update a book detail                 | `/api/v1/books/:bookId`   |
| GET    | To get details of a particular book     | `/api/v1/books/:bookId`   |
| DELETE | To remove a book                        | `/api/v1/books/:bookId`   |


## Tests


- To run test for all endpoints
  > run the command below
  ```shell
  $ npm run test
  ```
