# Steps

1. Run `npm init -y` to create a package json file.
2. Install packages required. Usual - express, sqlite3, knex, nodemon -D. Run `npm i express sqlite3 knex` and `npm i nodemon -D`
3. Add `"server": "nodemon index.js"` as a script on package.json
4. Add an index.js file and a server.js file.
5. Set up index.js (import server,js, define a port, server.listen ...).
6. Set up server.js (import express, create a const server etc) **_ Don't forget to export!!! _**
7. Create a folder for your routes. eg auth for authentication routes
