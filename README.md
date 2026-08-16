# SRM Timetable Dashboard

A mobile-first, dark-mode timetable dashboard built with plain HTML, Tailwind CSS via CDN, and vanilla JavaScript.

## Features

- Reads the current local date automatically
- Loads `schedule_data.json` from the same folder
- Resolves the academic day order from the calendar
- Shows class cards with time, subject, building, room, and faculty
- Handles holiday and empty-day states gracefully
- Works well on mobile and desktop
- Ready for static hosting on GitHub Pages

## GitHub Pages setup

1. Push this project to a GitHub repository.
2. In the repository settings, open **Pages**.
3. Choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Save. GitHub will publish the site at the URL shown in the Pages section.

## Local preview

Open `index.html` directly or run a local static server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000/`.
