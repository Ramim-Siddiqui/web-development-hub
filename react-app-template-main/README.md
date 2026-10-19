# React App Template

A minimal starter template for a multi-page React site. It ships with a header, footer and Home / About / Contact pages already wired up with client-side routing, so a new project can start from a working layout instead of a blank Create React App install.

**Stack:** React 18 (Create React App), React Router v5, React-Bootstrap 5.

## How to run

```
npm install && npm start
```

The dev server opens at http://localhost:3000.

## Where to look

- `src/components/Routing.js` - route table (`/`, `/home`, `/about`, `/herosection`, `/contact`)
- `src/components/` - one file per page, plus `Header.js` and `Footer.js`
- `src/App.js` - wraps `Routing` in `BrowserRouter`
