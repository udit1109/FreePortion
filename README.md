# FreePortion

Angular Full Stack
The frontend is generated with Angular CLI. The backend is made from scratch. Whole stack in TypeScript.
This project uses the MEAN stack:


Mongoose.js (MongoDB): database

Express.js: backend framework

Angular 4: frontend framework

Node.js: runtime environment


Prerequisites

Install Node.js and MongoDB

Install Angular CLI: npm i -g @angular/cli

From project root folder install all the dependencies: npm i



Run

Development mode
npm run dev: concurrently execute MongoDB, Angular build, TypeScript compiler and Express server.
A window will automatically open at localhost:4200. Angular and Express files are being watched. Any change automatically creates a new bundle, restart Express server and reload your browser.

Production mode
npm run prod: run the project with a production bundle and AOT compilation listening at localhost:3000
