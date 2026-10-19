# Web Development Hub

A collection of small front-end practice projects and starter templates kept together in one repository. Each project was built to practise a specific idea, from a static HTML/CSS layout to small React apps with routing and state.

## Projects

| Project | Description | Stack | How to run |
|---|---|---|---|
| [Login_Page-main](./Login_Page-main) | Static sign-up / login page layout with email and password fields and social sign-up buttons | HTML, CSS | Open `index.html` in a browser |
| [react-app-template-main](./react-app-template-main) | Starter template with a header, footer and Home / About / Contact pages wired up with React Router | React (CRA), React Router v5, React-Bootstrap | `npm install && npm start` |
| [react-digital-clock-main](./react-digital-clock-main) | Live digital clock that updates every second using `useState` and `useEffect` | React (CRA), React-Bootstrap | `npm install && npm start` |
| [react-portfolio-template](./react-portfolio-template) | Personal portfolio site with Home, About, Skills, Projects and Contact pages | React (CRA), React Router v5, React-Bootstrap, Font Awesome | `npm install && npm start` |
| [react-to-do-list-app-main](./react-to-do-list-app-main) | To-do list where tasks can be added and removed, with state held in React | React (CRA), React-Bootstrap | `npm install && npm start` |

## Notes

- Each folder is self-contained with its own dependencies and configuration. There is no shared build at the root, so `cd` into a project folder before running any command.
- The React projects were bootstrapped with Create React App and start a dev server at `http://localhost:3000`.
- `npm run build` produces a production bundle in each React project's `build/` folder.
