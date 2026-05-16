# Corporate Work OS

A premium static dashboard for Yuvraj Sureka to track internship/job execution, learning, manager support, reflections, reminders, analytics, and review-ready exports.

## Profile Built In

- Name: Yuvraj Sureka
- Company: Verity Knowledge Solutions
- Position: Analyst
- Department: Products
- GPN: 43897833

These credentials appear in the sidebar, profile card, dashboard greeting, CSV export, JSON backup, and printable PDF report.

## No Demo Data

The app ships with no sample tasks, fake metrics, dummy charts, or placeholder work records. All dashboard metrics, charts, Kanban cards, calendar items, and reports are generated only from records entered through the UI.

## Features

- Daily Work Log with priority, assignee, deadline, department, time, status, notes, outcome, learning, challenges, solution, and impact.
- Manager Support Tracker for process improvement, automation, reports, errors prevented, time saved, and initiatives.
- Learning Dashboard for skills, Excel/VBA/Python concepts, finance concepts, communication improvement, mistakes, and lessons.
- Reflection System for what went well, improvement areas, biggest win, biggest challenge, and tomorrow's focus.
- Notifications and reminders.
- Dashboard analytics, dynamic charts, completion rate, productivity index, average completion time, weekly trends, department-wise hours, learning hours, and efficiency score.
- Search, advanced filters, tags, priority color coding, calendar view, Kanban board, status updates, dark/light mode, edit/delete actions, and empty states.
- Export to printable PDF, Excel-ready CSV, and JSON backup.
- Local persistence using `localStorage`, so data stays after refresh.

## File Structure

```text
.
|-- index.html
|-- styles.css
|-- server.mjs
|-- package.json
|-- README.md
`-- src
    |-- analytics.js
    |-- export.js
    |-- main.js
    `-- storage.js
```

## Run Locally

```bash
npm install
npm run dev
```

Open `http://localhost:4173`.

## Dependencies

There are no runtime dependencies. The project is intentionally static so it can be hosted directly on GitHub Pages.

## Deploy to GitHub Pages

1. Create a GitHub repository.
2. Upload this project folder or push it with Git.
3. In GitHub, open `Settings > Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Select your branch and the root folder.
6. Save. GitHub will publish the site after the Pages build completes.

Because the app stores data in the browser, each browser/device has its own saved workspace. Use `Download Backup` before clearing browser data or moving devices.
