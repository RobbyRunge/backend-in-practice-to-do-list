# Todo List

A simple todo list project using [json-server](https://github.com/typicode/json-server) as the backend and Vanilla JavaScript as the frontend.

## Prerequisites

- [Node.js](https://nodejs.org/) installed

## Start the Backend

Install json-server globally:

```bash
npm install -g json-server
```

Start the backend with your database file:

```bash
json-server --watch db.json
```

The backend is now running at [http://localhost:3000](http://localhost:3000).

## Start the Frontend

Open the `index.html` file in your browser.

## Notes

- The todos are available at `/todos`.
- Changes to the `db.json` file are automatically applied.
- The frontend accesses the data via `fetch('http://localhost:3000/todos')`.

---
