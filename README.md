# Daymark

Daymark is a responsive, dark-themed task manager for organizing personal and work tasks. Create lists, schedule tasks by date and time, track completion, and find tasks with search and built-in views.

## Live Demo

https://shreya-pp.github.io/SCT_WD_4/

The site is published from the repository's `main` branch using GitHub Pages. The first deployment becomes available after the Pages workflow completes successfully.

## Features

- Create custom lists and organize tasks by list.
- Add tasks with optional due dates and times.
- Edit task names, lists, dates, and times.
- Mark tasks complete, restore them to active, or delete them.
- Browse All Tasks, Today, Upcoming, Completed, or an individual list.
- Search tasks by name and see completion progress.
- Save tasks and lists in browser local storage so they remain after a reload on the same device and browser.
- Use the responsive blue, deep-blue, and black-purple interface on desktop and mobile.

## Run Locally

No dependencies, build step, or backend are required. Open `index.html` directly in a modern browser, or serve the project directory with any static web server.

## Data and Privacy

Daymark stores tasks in the browser using `localStorage`. Data is not synced to an account or shared between browsers or devices. Clearing the browser's site data removes saved tasks and lists.

## Technology

- HTML
- CSS
- Vanilla JavaScript
- Browser `localStorage`
- GitHub Pages for hosting

## Deployment

The workflow in `.github/workflows/pages.yml` deploys `index.html` to GitHub Pages when changes are pushed to `main`, or when the workflow is started manually from GitHub Actions. Repository Pages publishing is configured by the workflow.