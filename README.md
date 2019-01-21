## Questions

1. What is responsible for defining the routes of the `games` resource?
The server.js and the create_router helper.

2. What are the the responsibilities of server.js?
Configuring the server - providing paths for uploading files to the browser.

3. What are the responsibilities of the `gamesRouter`?
It stores the games data.

4. What process does the the client (front-end) use to communicate with the server?
Get requests

5. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs
It takes in id as an argument. It returns the string of the url and id so it can be deleted using the delete method

6. Which of the games API routes does the front-end application consume (i.e. make requests to)?
The gets for index and show.

7. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?
Storing non-relational data.

## Extension

Why do we need to use [`ObjectId`](https://mongodb.github.io/node-mongodb-native/api-bson-generated/objectid.html) from the MongoDB driver?
ObjectId is a system generated id we can use to access the collection.
