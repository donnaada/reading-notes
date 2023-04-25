# 🗒️ Class 12

## Status Codes Based On REST Methods

- In your own words, describe what each group of status code represents:

  - 100’s =  This group of code represents the connection or any other informational status code
  - 200’s = This group of code represents success codes
  - 300’s = This group of code represents redirection codes
  - 400’s = This group of code represents *Client* error codes
  - 500’s = This group of code represents *Server* error codes
- What is a status code 202? 
  > Status code 202 is the *Accepted* status code

- What is a status code 308?
  > Status code 308 is the *Permanent Redirect* code

- What code would you use if an update didn’t return data to a client?
  > Status Code 204 - No Content

- What code would you use if a resource used to exist but no longer does?
  > Status Code 410 - Gone

- What is the ‘Forbidden’ status code?
  > Status Code 401

## Build A REST API With Node.js, Express, & MongoDB

- Why do we need to pull our MongoDB database string out of our server and put it into our .env?
  > We put that string into our .env file because it contains our db's admin username and password

- What is middleware?
  > Middleware is code that handles code between te client and server

- What does app.use(express.json()) do?
  > Allows an app to use JSON data in the request body.

- What does the /:id mean in a route?
  > It means its a dynamic route

- What is the difference between PUT and PATCH?
  > PUT updates the entire file and PATCH is a partial update

- How do you make a default value in a schema?
  > By adding the `default` property in the schema definition

- What does a 500 error status code mean?
  > Status 500 is a server error

- What is the difference between a status 200 and a status 201?
  > 200 is a success code and 201 is a success code but also signifies the backend resource has been created.
