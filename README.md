# DSA Tracker

A free, self-hosted daily practice tracker for frontend developers prepping for DSA (Data Structures & Algorithms) interviews. No sign-up, no backend, no build step — open it and start Day 1.

**Live app:** https://dsa-tracker-213.vercel.app

## Why this exists

DSA prep is easy to plan and hard to actually stick to, especially for frontend developers whose day-to-day work rarely touches algorithms. This tracker is built around one idea: make the daily habit as frictionless as possible, and make progress visible enough that you don't want to break the streak.

## Features

- **84-day, 12-week curriculum** — Arrays through Dynamic Programming, with inline LeetCode-style problem statements
- **Gated hints** — a 💡 button reveals a technique hint only when you tap it, so you try first
- **3 practice tracks** — Classic Core, Trend Track, and an Emerging Track for newer problem patterns
- **Streaks & badges** — daily check-ins, a streak counter, and 11 unlockable achievements
- **"No-hint solve" tracking** — a separate stat for problems you solved without peeking
- **84-day heatmap** — a GitHub-style contribution grid; tap any day to jump straight to it, with left/right arrow navigation between days
- **Daily reminders** — a configurable reminder time and a 10 PM nudge if you haven't started, while the app is open
- **Challenge links** — generate a `?challenge=N` link and dare a teammate to match your streak
- **Shareable progress** — a LinkedIn share sheet with dynamic post text, your earned badges, and a downloadable PNG stat card
- **Installable PWA** — works offline, installs to your home screen on iOS and Android

## Stack

Vanilla JavaScript. A single `index.html` + `sw.js`. No framework, no build step, no backend — all progress lives in your browser's `localStorage`.

Deployed on [Vercel](https://vercel.com) with CI/CD from `main`.

## Running locally

There's nothing to build. Clone the repo and open `index.html` in a browser, or serve it with any static file server:

```bash
git clone https://github.com/proS1996/dsa-tracker.git
cd dsa-tracker
npx serve .
```

## Feedback & contributing

This started as a personal project to keep my own prep on track, and it's grown from there. If you use it and have ideas — missing problems, features that would help your prep, bugs — issues and PRs are welcome. If it's useful to you, a ⭐ on the repo genuinely helps and is motivation to keep building tools like this.

## Roadmap ideas

- A real cross-team leaderboard (currently deferred to keep the app backend-free)
- More curated problem sets and difficulty tiers
- Export/import progress data

## License

No license file yet — treat it as source-available for personal use; open an issue if you'd like to build on top of it.
