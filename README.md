# React Client with Express Server
Created: 05 April 2022
Last Updated: 05 April 2022

# What
This is a boilerplate template for a very basic React Client served through a very basic Node-Express server.
It's meant to be the starting point for more complex projects built with React and Express.

The React Client is located in the client folder, while the Node-Express server is located in the server folder.
Both the client and the server folder have their own package.json files describing all the necessary dependencies and script commands.
The command to build the React Client will build the project inside server/public folder.
The Node-Express server is then set to serve the static index.html file from the server/public folder.

# How to use
- Clone or downlaod the repository.
- Install all dependencies for both the client and server folders:
- Client dependencies = CD into client folder run: npm install
- Server dependencies = CD into server folder run: npm install
- Work on React Client in client/src folder
- Work on Express Server in server/src folder
- Build the React project from the main root folder with: npm run deploy-client. You can also build the React project from the client folder with: npm run build. Both commands will build the React project inside the server/public folder.
- Start the Express server from the main root folder with: npm run server. You can also start the Express server from the server folder with: npm start.
- In your browser navigate to localhost:8000 to view the React app serverd through Express server.

# Next feature to implement
- Start the Express server automatically when the React client is deployed.
- Add nodemon to watch changes to the Express server and automatically refresh localhost:8000

# Who
I am the only author of this repository:
Riccardo
riccardop@outlook.com

# Status
This boilerplate has been created in April 2022.
I'll keep adding features as required.

# npm script commands in "root" folder
```
npm run server
```
- Start the express server on port 8000

```
npm run client
```
- Start the the React client with the React developing server on port 3000

```
npm run deploy-client
```
- Build the React project inside server/public folder. When running the express server the files from server/public will be served on localhost:8000.

# npm script commands in "server" folder
```
npm start
```
- Start the express server on port 8000

# npm script commands in "client" folder
```
npm start
```
- Start the the React client with the React developing server on port 3000

```
npm run build
```
- Build the React project inside the server/public folder.