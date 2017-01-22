# MovieStore
A demo Movie Store app built with Node.js, MongoDB, Express and Nunjucks(The Mozilla server-side templating engine)

#### Setup the environment
1. Install Node.js v6.9.2 (https://nodejs.org/en/download/)
2. Install MongoDB v3.2.3 (https://www.mongodb.com/download-center)

#### Start MongoDB Server

In a cmd, type :
`...\MovieStore> mongod`

#### Create new Database

In a new cmd, open the MongoDB Shell by typing
`...\MovieStore> mongo`

then, create a new database
`...\MovieStore> use video`

#### Populate the Database

Copy/Paste this code to the MongoDB Shell
`db.collection('movies').insertOne({ "title": "Jaws", "year": 1975, "imdb": "tt0073195" });`
`db.collection('movies').insertOne({ "title": "Mad Max 2: The Road Warrior", "year": 1981, "imdb": "tt0082694" });`
`db.collection('movies').insertOne({ "title": "Raiders of the Lost Ark", "year": 1981, "imdb": "tt0082971" });`

#### Install Node.js Dependencies

In a new cmd, type :
`...\MovieStore> npm install`

#### Run App

In the same cmd, run this command :
`...\MovieStore> node-dev app`

Then open this url in your browser : http://localhost:3000
