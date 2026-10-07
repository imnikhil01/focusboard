# FocusBoard

A simple Pomodoro timer and task tracker in a single web page. No installs, no frameworks, no backend.

## Features

- 25-minute focus and 5-minute break timer with a progress ring
- Start, pause, and reset controls
- Task list: add, complete, and delete tasks
- Counter for focus sessions finished today
- Sound alert when a session ends
- Countdown shown in the browser tab title
- Tasks and stats saved in the browser (localStorage), so they survive a refresh
- Responsive dark UI for phone and laptop

## Tech

- HTML, CSS, and vanilla JavaScript in one file (`index.html`)
- Timer uses timestamps, so it stays accurate even if the tab is throttled
- Web Audio API for the end-of-session beep
- localStorage for persistence, wrapped in `try/catch` so the app still works if storage is blocked

## Run locally

1. Clone or download this repo.
2. Open `index.html` in any browser.

## Deploy on GitHub Pages

1. Push `index.html` to a public repo.
2. Go to **Settings → Pages**.
3. Under Source, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. Your site is live after about a minute.

## Ideas for next steps

- Custom focus and break lengths
- Link a session to a specific task
- Weekly stats chart
- Installable PWA

## Author

Built by Nikhil Sachdeva.
