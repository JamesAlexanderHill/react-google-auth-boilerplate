# react-firebase-boilerplate
A boilerplate React app with Firebase authentication

# Development
run `npm run watch`

This will run the ExpressJS server and ReactJS application separately and reload each one independantly when changes are made.

Server Port: `process.env.SVR_PORT` or `3001`

ReactJS Port: `3000`

# Production
run `npm run start`

This will run the ReactJS build script and serve the files via an ExpressJS server in a Docker container.


Port: `process.env.PROD_PORT` or `80`