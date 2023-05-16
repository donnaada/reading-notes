# 🗒️ Class 03: Express REST API

## Readings

### Review: ES6 Classes

- Classes are a template for creating ____
  > Object

- Can a class declaration be hoisted?
  > No, class declarations are not hoisted and cannot be used before it is declared, similar to variables declared with `let` and `const`.

- How would you describe a constructor and contextual “this” to a non-technical friend?
  > A constructor is a method used for creating objects within a class. The contextual 'this' refers to the object created by the constructor.

### Using Express Routing

- Within Express, what does routing refer to?
  > Routing refers to the application's URI endpoint.

- What is the difference between a route path and a route method?
  > A method refers to one of the HTTP methods (POST, PUT, DELETE, POST, etc) that is attached to the middleware and path is the endpoint association with a specific route method.

- When is it appropriate to add next as a parameter to a route handler and what must you
do if next has been passed to your middleware as a parameter?
  > We can add `next` as a parameter when we want to set pre-conditions on a specific route and then pass the control to the next route when there is no reason to use it in the current one. If we pass `next` as a parameter`, we must call on it within the function in order to pass control.

### Express Routing

- What is an Express Router?
  > Express Router is a mini-express application that only uses the routing API.

- By what mean do we initialize express.Router() in an express server?
  > In order to initialize express.Router(), we need to include it into our `package.json` file and run `npm install` to make sure our dependencies are installed.  Once that is done, we add express into our server.js file then add the router instance.

- What do we use route middleware for?
  > We use the route middleware as a way to do something (like authentication, data logging, etc) before the request is processed.
