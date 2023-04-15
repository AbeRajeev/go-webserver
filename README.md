# go-webserver

A simple HTTP server that serves a REST API for a todo list application.

The server should have the following endpoints:

GET /todos - returns a JSON array of all todos
POST /todos - adds a new todo to the list
GET /todos/:id - returns the todo with the specified ID
PUT /todos/:id - updates the todo with the specified ID
DELETE /todos/:id - deletes the todo with the specified ID
Each todo should have the following fields:

ID: unique identifier for the todo (integer)
Title: title of the todo (string)
Completed: whether the todo has been completed (boolean)
The server should store the todos in memory (i.e., no database is required).

Libraries to use: 

net/http: for handling HTTP requests and responses
encoding/json: for encoding and decoding JSON data
