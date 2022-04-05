# React Client with Express Server
Created: 05 April 2022
Last Updated: 05 April 2022

# WHAT
This is boilerplate template for a very basic React Client served through a very basuc Node-Express server.
It's meant to be the starting point for more complex projects built with React and Express.

The React Client is located in the client folder, while the Node-Express server is located in the server folder.
Both the client and the server fodler have their own package.json files describing all the necessary dependencies.
The command to build the React Client will build the project inside server/public folder.
The Node-Express server is then set to serve the static index.html file from the server/public folder.

# Who
I am the only author of this application:
Riccardo
riccardop@outlook.com

# Status
This boilerplate has been created in April 2022.
I'll keep adding features as required.

# npm script commands in "root" folder
npm run server
- Start the express server on port 8000

npm run client
- Start the React client on port 3000

npm run deploy-client
- Build the React project inside server/public folder. When running the server the files from server/public will be served on localhost:8000.

# npm script commands in "server" folder
npm start
- Start the express server on port 8000

# npm script commands in "client" folder
npm start
- Start the React client on port 3000

npm run build
- Build the React project inside server/public folder.