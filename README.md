# MERN Stack Login/Auth App 

This is a minimal full-stack Login/Register Application with MERN Stack. 
This repo created when I was learning from [this medium series](https://blog.bitsrc.io/build-a-login-auth-app-with-mern-stack-part-1-c405048e3669).

## Overview

This app will allow users to
- Register
- Log in
- Access protected pages only accessible to logged in users
- Stay logged in when they close the app or refresh the page
- Log out


## Configuration

You must add your own ```MONGOURI``` in ```config/keys.js```

```bash
module.exports = {
  mongoURI: "YOUR_MONGO_URI_HERE",
  secretOrKey: "secret"
};
```

## Running Locally

```bash
$ git clone https://github.com/alihan/mern-auth.git
$ cd mern-auth
$ npm install && npm run client-install // Install dependencies for server & client
$ npm run dev // Run client & server with concurrently

Server runs on http://localhost:5000 and client on http://localhost:3000
```

## Built Using

- [React](https://reactjs.org) and [React Router](https://reacttraining.com/react-router/) for the frontend
- [Express](http://expressjs.com/) and [Node](https://nodejs.org/en/) for the backend
- [MongoDB](https://www.mongodb.com/) for the database
- [Redux](https://redux.js.org/basics/usagewithreact) for state management
