# 🗒️ Class 02: Express, NPM, TDD, CI/CD

## Reading

### An introduction to NodeJS and Express

- Explain middleware, answer as though I were a non-technical recruiter.
  - Middleware is the bridge between the data on the back end (server side) and what is displayed on the screen (front-end/ client side)
- Express the most popular __ __ ____.
  - Node Web Framework
- Express is “unopinionated.” What does that mean?
  - That means that there are fewer restrictions on how components are pieced together to create a working product.
- What is a module and why is modularity useful to us as developers?
  - Modules are block of code that can be stored in external .js files and are imported into other code using the `require()` function. Modularity is useful because they are reusable chunks of code that can easily be used in other code projects.

### What is NPM?

- What version of npm are you running on your machine?
  - npm v. 9.6.6
- What command would you type to install a library/package called ‘jshint’ into your node project?
  - `npm install jshint` to install it only in a specific node project or `npm install -g jshint` to install JSHint globally.

### What is TDD?

Test Driven Development

- Explain why tests are important. Please explain as though I were your non technical elder.
  - Tests are important because they help ensure that the code does what it is intended to do. Also, by testing early on and often, we can catch bugs sooner and resolve any issues.
- What are three expected benefits of testing
  - ignificant reductions in defect rates, at the cost of a moderate increase in initial development effort
  - Overheads are more than offset by a reduction in effort in projects’ final phases
  - Leads to improved code design quality and a higher degree of "internal" or technical quality.
- Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
  - Individual
    - Writing too many tests at once
    - Writing overly Trivial tests
  - Team
    - Abandoned test suite
    - Parital Adoption of test suite

### CI/CD

[GitHub CI/CD Article](https://resources.github.com/ci-cd/)

- What are three benefits of Continuous Integration?
  - Code is automatically Built, Tested, and Integrated to a shared repository.
- What is the difference between Continuos Delivery and Continuous Deployment?
  - With continous deliveryu, each successful build is pushed to each pre-production environment where as continous deployment automatically pushes to the production site.
- Explain how GitHub fits into this process assuming the listener comes from a non-technical background
  - GitHub provides developers with a place to store, manage, build, test, and promote their code and projects. GitHub also integrates with other services like Render and Netlify to allow for testing, building, and deploying of front-end and back-end repositories.