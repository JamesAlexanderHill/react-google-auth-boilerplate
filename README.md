# react-firebase-boilerplate
A boilerplate React app with Firebase authentication

## Development
`npm run watch`

This will run the ExpressJS server and ReactJS application separately and reload each one independantly when changes are made.

Server Port: `process.env.SVR_PORT` or `3001`

ReactJS Port: `3000`

## Production
`npm run start`

This will run the ReactJS build script and serve the files via an ExpressJS server in a Docker container.


Port: `process.env.PROD_PORT` or `80`

## .env variables
Some `.env` variables that need to be defined in the root of the project:

- `SVR_PORT` - `3001` by default
- `PROD_PORT` - `80` by default
- `NODE_ENV` - `production` or `development`
- `API_KEY` - Firebase config
- `AUTH_DOMAIN` - Firebase config
- `PROJECT_ID` - Firebase config
- `STORAGE_BUCKET` - Firebase config
- `MESSAGING_SENDER_ID` - Firebase config
- `APP_ID` - Firebase config

Also you need to set the `GOOGLE_WEB_CLIENT_ID` in `client/src/util/constants.js`.