# MERN-user-authentication-boilerplate
Repo for basic auth setup for MERN stack application using name, email, and password and authenticating with json web tokens

## Getting Started
Once you have cloned the repo in the root directory of your project run `npm install` to install dependencies.

This project assumes that you are using MongoDB Atlas.

To sign in or learn more click [here](https://www.mongodb.com/cloud/atlas).

Once in MongoDB Atlas, generate a new cluster. Once the cluster is built, click the connect button and choose Connect your Application and copy the string and place it in the default.json file in the config directory for your mongoUri.

Add your jwtSecret in the same file.

## Add Client Files
Run `npx create-react-app client` to add client files to the application. This will allow you to run `npm run dev` to run the client server and database server at the same time using concurrently.
