What is responsible for defining the routes of the games resource?
Express


What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?
Client is frontend is responsible for user input
Server is responsible for responding 
Vue = frontend
Express = backend
Client is responsible for front end work such as formatting and design, events and components. Holds Vue.
Server is responsible for backend.
Holds the database and the routes.

The folder structure holds our front and backend sides including databases, events and components

What are  the responsibilities of server.js?
It’s the main code to initiate the routes 
It’s in charge of the main code for the server


The server holds  the cors which holds our security functionality 
Holds parser.json which allows us to access the body
It holds our database and app.listen which listens out for our routes 

What are the responsibilities of the gamesRouter?
Looking out for requests on the routes looking out for get and post requests.
The responsibilities of the gamesRouter is to organise the routes for the games table of the database.


What process does  the client (front-end) use to communicate with the server?
The client front end uses the API 
What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs
The second argument is an init object that allows you to control a number of different settings such as methods, post methods, body and headers.


Which of the games API routes does the front-end application consume (i.e. make requests to)?
The front end consumes the post, delete and get
Responsible for talking to the backend
Front end code responsible to talking to the API backend

What are we using the MongoDB Driver for? 
MongoDB creates non-relational database (non-sql relationship)
DB, collection, documents
MongoDB Node.js driver allows Node.js applications to connect to MongoDB and work with data
