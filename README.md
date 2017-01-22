# MovieStore
A demo Movie Store app built with Node.js, MongoDB, Express and Nunjucks(The Mozilla server-side templating engine)

#### Start MongoDB Server

`mongod`

#### Create new Database

`use video`

#### Populate the Database

`db.collection('movies').insertOne({ "title": "Jaws", "year": 1975, "imdb": "tt0073195" });`
`db.collection('movies').insertOne({ "title": "Mad Max 2: The Road Warrior", "year": 1981, "imdb": "tt0082694" });`
`db.collection('movies').insertOne({ "title": "Raiders of the Lost Ark", "year": 1981, "imdb": "tt0082971" });`

#### Install Node.js Dependencies

`npm install`

#### Run App

`node app`

Then open this url in your browser : http://localhost:3000
