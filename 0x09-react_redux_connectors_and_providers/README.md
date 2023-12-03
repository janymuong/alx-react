# React Redux Connectors and Providers

> This project is an illustration of using React with Redux, emphasizing the use of Connectors and Providers. It provides a structure to connect React components to the Redux store using `connect` and use the `Provider` component for efficient state management.

## Usage

- Run the development server:

- Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

The project structure is organized as follows:

```bash
# a sketchy structure would look like this;
│
├── src/
│   ├── components/       # components
│   ├── containers/       # components connected to Redux using connectors
│   ├── reducers/         # reducers
│   ├── store/            # store configuration
│   ├── actions.js        # action creators
│   └── index.js          # entry point for the application
│
└── ...
```

## Redux Setup

Redux is configured in the `src/store` directory. It includes the store configuration, middleware setup, and root reducer.

## Connectors

Connectors, located in the `src/containers` directory, are higher-order components that connect your React components to the Redux store using the `connect` function. They define how to transform the current Redux store state into the props that your component needs.

## Providers

The `Provider` component from the `react-redux` library is used to wrap your entire application. It makes the Redux store available to all components in the component tree, eliminating the need to pass it down manually through each level.

---
#### Random Usage Example
```jsx
// src/index.js

import React from 'react';
import ReactDOM from 'react-dom';
import { Provider } from 'react-redux';
import store from './store';
import App from './components/App';

ReactDOM.render(
  <Provider store={store}>
    <App />
  </Provider>,
  document.getElementById('root')
);
```
