# Weekly Project Check-in

An internal tool for tracking weekly project status across a small research centre. Built with plain HTML/JS, hosted on GitHub Pages, data stored in Firebase.

## Pages

| Page | URL | Access |
|------|-----|--------|
| **Detailed dashboard** | [index.html](https://sequoia-kim.github.io/weekly-project-updates/index.html) | View responses, flags, and weekly summaries - for Operations, Management and Admin |
| **Team view** | [team.html](https://sequoia-kim.github.io/weekly-project-updates/team.html) | Read-only project status and calendar for all team members|

## Stack

- **Frontend** — HTML, CSS, vanilla JS (no framework)
- **Database** — Firebase Realtime Database
- **Auth** — Firebase Email/Password
- **Hosting** — GitHub Pages via GitHub Actions

## Setup

Requires three GitHub Secrets set in repo settings:

| Secret | Description |
|--------|-------------|
| `FIREBASE_URL` | Firebase Realtime Database URL |
| `FIREBASE_API_KEY` | Firebase project API key |

Secrets are injected into the HTML at deploy time. Firebase Authentication must have Email/Password enabled, with user accounts created manually in the Firebase console.
