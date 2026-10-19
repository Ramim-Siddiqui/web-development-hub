# React Digital Clock

A full-screen digital clock that shows the current hours, minutes, seconds and AM/PM and re-renders every second. Built as a small exercise in React state and effects.

**Stack:** React 18 (Create React App), React-Bootstrap 5.

## How to run

```
npm install && npm start
```

The dev server opens at http://localhost:3000.

## Where to look

- `src/components/Herosection.js` - the whole clock: `useState` holds a `Date`, `useEffect` starts a one-second `setInterval`, and the layout uses React-Bootstrap `Container` / `Row` / `Col`
- `src/App.js` - renders `Herosection`
