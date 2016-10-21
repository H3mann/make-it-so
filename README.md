# make-it-crow

Inverse kickstarter application. Users can submit requests, referred to as'bounties' in our app, for a project to be created. There are features for payment using Stripe, automated tweets once a bounty is created and leading bounties. 

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.  Npm is used to install dependencies, which are stored in node_modules. The Node/Express server connects to a remote SQL database. To run locally from your terminal:

1. Git clone and cd into root of directory of the project.
2. npm install
3. node server/server.js - to run the server.
4. go to http://localhost:8000/#/ in your browser.

##Deployed version
App is deployed on AWS: http://ec2-52-91-187-232.compute-1.amazonaws.com/

## Tech Stack
- Front End: AngluarJS
- Back End: NodeJS/Express
- Database: mySQL/Bookshelf/knex

