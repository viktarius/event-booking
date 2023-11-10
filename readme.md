# EasyEvent

## Overview
EasyEvent is an application for organizing and managing events. It was developed using Node.js, Express, React.js, and MongoDB, as well as GraphQL and Git submodules.

## Installation
To initialize the project, clone this repository and run the following commands in the project folder:
```
git submodule init
git submodule update
```
After that, navigate to each installed module and run `npm install`.

## Getting Started
To start the application, you will need to run both the front-end and back-end servers.

To start the front-end server, navigate to the `event-booking-fe` directory and run:
```
npm start
```

To start the back-end server, navigate to the `event-booking-be` directory and create a `.env` file with the necessary environment variables. These variables are required for the app to function properly. The required environment variables are:
```
JWT_TOKEN_SECRET_KEY=<Insert your secret key for JWT token>
MONGO_DB=<Insert your MongoDB DB>
MONGO_PASSWORD=<Insert your MongoDB password for user>
MONGO_USERNAME=<Insert your MongoDB user>
```
Then, run:
```
npm start
```
This will launch both servers. Additionally, the application can be accessed via the browser at `localhost:3000`.

Please note, this is assuming that you have MongoDB installed, and have an account with an established MongoDB database URL. If you haven't done this already, please create an account at MongoDB and input your database URL.

## Features
- User authentication
- Event creation and management
- User and event subscriptions
- Event search functionality

## Technology Stack
- Node.js
- Express
- React.js
- MongoDB
- GraphQL
- Git submodules

## Contributions
Contributions and feedback are welcome and appreciated. If you would like to contribute, please submit a pull request or an issue.
