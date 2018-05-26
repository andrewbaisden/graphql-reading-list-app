# GraphQL User Dashboard App

## Prerequisite

You need to setup a MongoDB Database otherwise this App wont work. Either create a local database or create an account on https://mlab.com/home

Then add the database mongoLab URI to server/server.js. Make sure that you create a user and a password for the login.

Example code in server/server.js file below:

```javacript
// Replace with your mongoDB URI
const API = 'mongodb://<dbuser>:<dbpassword>@ds111111.mlab.com:11111/databasename';
```

http://docs.mlab.com/connecting/#connect-string

## Install and Setup

Run the command below in the root of the client, and server folders to install the node_modules dependencies

```javascript
npm install
```

Run the command below in the root of the server folder, to start the app

```javascript
npm run dev
```

The App is running at http://localhost:3000/
