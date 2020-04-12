# Create an end-to-end Rest API POC using Express, Mongoose, Swagger.

## Features

- [Routing](#routing)
- [Create Schemas](#create-schemas)
- [Controllers](#controllers)
- [Authentication](#authentication)
- [Testing](#testing)

## Resources

- [Nodejs](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)

## Tech utilized

- Express 4
- Mongoose 5
- Morgan (logging)

## Set-up - Database

- Install home brew for quick installation - `brew tap mongodb/brew`
- Install mongo db - `brew install mongodb-community@4.2`
- Run Mongodb - `mongod --config /usr/local/etc/mongod.conf`
- Questions? - Please refer - https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/

## Set-up - Application

- npm install
- Start server - `npm run dev`
- Build directory - `npm run build` (optional)
- Open application via `http://localhost:1234/`

## API urls for reference

- / - get all records (GET)
- / - post new record (POST)
- /:id - update any existing record (PUT)
- /:id - delete any existing record (DELETE)

### Testing

- `npm run test-routes` - Test all the routers
- `npm run test-models` - Test all the models/tables including data type
- `npm run test-controllers` - Test controllers if any authentication is required
