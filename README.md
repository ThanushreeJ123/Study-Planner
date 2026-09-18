# Studyflow

Studyflow is a simple browser-based study planner for organizing tasks, tracking subjects, and planning study sessions.

## Features

- Overview dashboard with focus and study streak information
- Add, complete, and delete tasks
- Persistent task data using browser `localStorage`
- Add and delete subjects
- Adjust subject progress from 0% to 100%
- Persistent subject progress using browser `localStorage`
- Monthly calendar with previous, next, and today navigation
- Responsive layout for desktop and mobile screens

## Run Locally

The project is a single static HTML page and does not require a build step.

From the project folder, start a local server:

```powershell
python -m http.server 5500
```

Then open:

<http://localhost:5500/>

## Project Structure

```text
Study Planner/
├── index.html
└── README.md
```

## Data Storage

Tasks, subjects, and subject progress are saved in the browser's local storage. Data is specific to the browser and device being used.

## GitHub

Repository: <https://github.com/ThanushreeJ123/Study-Planner>
