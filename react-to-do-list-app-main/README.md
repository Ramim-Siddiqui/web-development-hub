# React To-Do List

A simple to-do list: type a task, add it to the list, and remove it with a button. Tasks are held in component state only, so the list resets on refresh. Built as a small exercise in React state and list rendering.

**Stack:** React 18 (Create React App), React-Bootstrap 5.

## How to run

```
npm install && npm start
```

The dev server opens at http://localhost:3000.

## Where to look

- `src/components/Herosection.js` - the to-do logic (`addTask`, `removeTask` on a `useState` array) and the form / `ListGroup` UI
- `src/components/Header.js`, `Footer.js` - page chrome
- `src/App.js` - composes the three components
