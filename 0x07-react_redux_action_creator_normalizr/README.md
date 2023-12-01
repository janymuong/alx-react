# React Redux Action `creator+normalizr`

> About React Redux Action `creator` + `normalizr`  
>> This project is a demonstration of using React with Redux, emphasizing the use of action creators and data normalization with Normalizr. It provides a basic structure to manage complex data structures in a Redux application.


Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

The project structure is organized as follows:

```
.
├── README.md
├── notifications.json
├── task_0
│   └── dashboard
...
│       ├── config
│       │   ├── setupTests.js
│       │   └── webpack.config.js
│       ├── dist
│       │   ├── favicon.ico
│       │   └── index.html
│       ├── package.json
│       └── src
│           ├── App
│           │   ├── App.js
│           │   ├── App.test.js
│           │   └── AppContext.js
│           ├── BodySection
│           │   ├── BodySection.js
│           │   ├── BodySection.test.js
│           │   ├── BodySectionWithMarginBottom.js
│           │   └── BodySectionWithMarginBottom.test.js
│           ├── CourseList
│           │   ├── CourseList.js
│           │   ├── CourseList.test.js
│           │   ├── CourseListRow.js
│           │   ├── CourseListRow.test.js
│           │   └── CourseShape.js
│           ├── Footer
│           │   ├── Footer.css
│           │   ├── Footer.js
│           │   └── Footer.test.js
│           ├── HOC
│           │   ├── WithLogging.js
│           │   └── WithLogging.test.js
│           ├── Header
│           │   ├── Header.js
│           │   └── Header.test.js
│           ├── Login
│           │   ├── Login.js
│           │   └── Login.test.js
│           ├── Notifications
│           │   ├── NotificationItem.js
│           │   ├── NotificationItem.test.js
│           │   ├── NotificationItemShape.js
│           │   ├── Notifications.js
│           │   └── Notifications.test.js
│           ├── assets
│           │   ├── close-icon.png
│           │   └── holberton-logo.jpg
│           ├── index.js
│           ├── schema
│           │   ├── notifications.js
│           │   └── notifications.test.js
│           └── utils
│               ├── utils.js
│               └── utils.test.js
├── task_1
│   └── dashboard
...

```

## Redux Setup

Redux is configured in the `src/` directory. It includes the configuration etc.

## Action Creators

Action creators, located in the `src/*` directory, are functions that return Redux actions. They are responsible for triggering changes to the Redux.

## Normalizr

Normalizr is a library for normalizing nested JSON-like data structures. Schemas for normalizing data are defined in the `src/` directory. Normalization simplifies the management of data in the Redux.
