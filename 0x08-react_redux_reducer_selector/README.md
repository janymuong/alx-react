# React Redux Reducer + Selector

This project is a entails using `React` with `Redux`, highlighting the implementation of *reducers* and *selectors*. It provides a basic structure to  manage state in a React application using Redux.


Visit [http://localhost:3000](http://localhost:3000) in your browser to verify how it works.

## Project Structure

The project structure is organized as follows:

```
.
├── README.md
├── task_0
│   └── dashboard
...
│       ├── dist
│       │   ├── favicon.ico
│       │   ├── index.html
│       │   ├── login-success.json
│       │   └── notifications.json
│       ├── login-success.json
│       ├── notifications.json
│       ├── package-lock.json
│       ├── package.json
│       └── src
│           ├── App
│           │   ├── App.js
│           │   ├── App.test.js
...
│           ├── index.js
│           ├── reducers
│           │   ├── uiReducer.js
│           │   └── uiReducer.test.js
│           ├── schema
│           │   ├── notifications.js
│           │   └── notifications.test.js
│           └── utils
│               ├── utils.js
│               └── utils.test.js
├── task_1
│   └── dashboard
...
│           └── utils
│               ├── utils.js
│               └── utils.test.js
...

```

## Redux Setup

Redux is configured in the `src/*` directory. It includes the configuration,and root reducer etc.

## Reducers

Reducers, located in the `src/*` directory, are responsible for handling state changes in the application. They specify how the state should change in response to actions.

## Selectors

Selectors, located in the `src/*` directory, are used to extract specific pieces of data from the Redux store. They are particularly useful for computing derived data or memoizing complex calculations.
