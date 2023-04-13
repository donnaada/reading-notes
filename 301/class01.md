# 🗒️ Class 01: Introduction to React and Components

[![altText](https://images.unsplash.com/photo-1614851099175-e5b30eb6f696?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80)](github)

## [Component-Based Architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

- What is a “component”?
  > Components are like functions. They are blocks of code that are reusable and can be called on when needed.

- What are the characteristics of a component?
  > Components are reusable, replaceable, and independent from other components.

- What are the advantages of using component-based architecture?
  > An advantage of using component-based architecture is the reusability of the blocks of code as well as the ability to upgrade, refactor, or remove components with it affecting the overall functionality of an application.

## [What is Props and How to Use it in React](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0#:~:text=%E2%80%9CProps%E2%80%9D%20is%20a%20special%20keyword,way%20from%20parent%20to%20child)

- What is “props” short for?
  > Props is short for Property. It is a special read-only keyword in React that is used to pass data from one component to another.

- How are props used in React?
  > Props are used to pass data from one component to another.

- What is the flow of props?
  > Props are uni-directional and flow from parent to child. Because of this, this means that data coming from the parent component shouldn't be altered by child components.

### Other Reading Resources

- [React Tutorial through ‘Passing Data Through Props’](https://reactjs.org/tutorial/tutorial.html)
- [React Docs - Hello world](https://reactjs.org/docs/hello-world.html)
- [React Docs - Introducing JSX](https://reactjs.org/docs/introducing-jsx.html)
- [React Docs - Rendering elements](https://reactjs.org/docs/rendering-elements.html)
- [React Docs - Components and props](https://reactjs.org/docs/components-and-props.html)

## Things I want to know more about

## Lecture Notes

`<> </>` is called fragment

`npx create-rect-app react-starter` checks online to see if there are any apps called create-rect-app and executes the command. *react-starter* is the title of the repo

after creating code that follows

```bash
Success! Created react-lab-01 at /home/dmaa/projects/courses/code301/labs/react-lab-01
Inside that directory, you can run several commands:

  npm start
    Starts the development server.

  npm run build
    Bundles the app into static files for production.

  npm test
    Starts the test runner.

  npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  cd react-lab-01
  npm start

Happy hacking!
➜  labs
```

- jsx allows you to do HTML style markup inside the HTML File

running `create-react-app` creates a repository
`git remote -v` lists out all the remote links on a repo

steps to create react app
run `npx create-react-app <repo name>`
create repo on github WITHOUT any README.md, License, or .gitignore files
copy and `push an existing repository from the command line`
