# Node-and-Express-Servers
Simple Node with Express + Server
Build Status Slack states 

An easy way to get started with a Express server with sql with Node.js. Read more about it.

Features
Babel 7
Environment Variables
Express
REST API
PostgreSQL
Requirements
node & npm
git
Installation
node-express-postgresql-server.git
cd node-express-postgresql-server
npm install
start PostgreSQL
npm start
optional: include .env in your .gitignore
GET Routes
visit http://localhost:3000
/messages
/messages/1
/users
/users/1
Beyond GET Routes
CURL
Create a message with:
curl -X POST -H "Content-Type:application/json" http://localhost:3000/messages -d '{"text":"Hi again, World"}'
Delete a message with:
curl -X DELETE -H "Content-Type:application/json" http://localhost:3000/messages/1
Postman
Install Postman to interact with REST API
Create a message with:
URL: http://localhost:3000/messages
Method: POST
Body: raw + JSON (application/json)
Body Content: { "text": "Hi again, World" }
Delete a message with:
URL: http://localhost:3000/messages/1
Method: DELETE
