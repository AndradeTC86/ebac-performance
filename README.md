# Ebac Performance

# Automation Test Perfomance with K6

This is the repository for automation of performance tests, developed to work with K6.

## Table of Contents

1. [Goal](#goal)
2. [Project Structure](#project-structure)
3. [Tests](#tests)
4. [Initial Setup](#initial-setup)
5. [Run Tests](#run-tests)

## Goal

The goal of this repository is to be easy to understand focused on developing automated performance tests for API, using [K6](https://k6.io), an open-source load testing tool that makes performance testing easy and productive for engineering teams.

## Project Structure

```
|--- data
|--- dist
|--- requests
|--- simulations
|--- utils
|--- .babelrc
|--- .env
|--- package-lock.json
|--- package.json
|--- webpack.config.js
```

## Tests

The tests were written using the JavaScript language with Grafana K6.

## Run tests

### Initial Setup

1. Requires node. To install, execute `npm install node` or download [Node](https://nodejs.org/en/download/)
2. Run the command `npm install` to install dependencies
3. Requires the EBAC Demo Store Server to execute. Git clone the [EBAC Demo Store Server](https://github.com/EBAC-QE/ebac-demo-store-server.git) for your local machine, then start following the steps in the README.

### Run Tests

- Run one of the commands below to run the tests.
  Examples:
- To run the perfomance test for the user API, execute `npm run test:user`
- To run the perfomance test for the products API, execute `npm run test:products`
- To run the perfomance test for the customers API, execute `npm run test:customers`
<p>