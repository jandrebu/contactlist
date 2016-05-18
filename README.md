Start Up

Go to project directory

Start node server
>node server

Start mongodb in another terminal
>mongod

View app in browser
localhost:3000


Install

1. Install Node.js

On Mac
Go to: https://nodejs.org/en/download/
Easiest to just click on Macintosh Installer and install

Install Express
npm install express

2. Install Mongodb
With brew
https://docs.mongodb.com/master/tutorial/install-mongodb-on-os-x/?_ga=1.257454091.1295667483.1462906445

- update brew
brew update

- install MongoDB
brew install mongodb

Run Mongo

- First time, create directory
mkdir -p /data/db

- run mongo
mongod


3. Install mongojs (interface between nodejs and mongodb)
mpm install mongojs

4. Install body parser, used by server to parse the body 
npm install body-parser
