# Asset & Repo Structure

Most of this README runs on hosted third-party widgets (shields.io, vercel capsule-render,
github-readme-stats, giphy) — **no assets need to live in your repo for those.** You only need
local/repo assets for two things: the snake animation and (optionally) a custom banner if you
want to move off capsule-render later.

## Required special repo

GitHub profile READMEs render from a repo with the **exact same name as your username**:

```
karthikk20234119-cmd/karthikk20234119-cmd/
├── README.md              ← this file, at repo root
├── .github/
│   └── workflows/
│       └── snake.yml      ← generates the snake contribution animation
└── output/                ← auto-created by the snake action, don't hand-edit
    ├── github-snake-dark.svg
    └── github-snake.svg
```

If this repo doesn't exist yet, create it (public), and the README you place at its root
becomes your GitHub profile page automatically.

## Optional local assets (only if you want to self-host instead of hotlinking)

```
assets/
├── banners/
│   └── header.svg          (only needed if replacing capsule-render banner)
├── icons/                  (only needed if replacing shields.io badges with custom icons)
└── screenshots/
    ├── agroguard-demo.png
    ├── face-attendance-dashboard.png
    └── homework-agent-flow.png
```

Screenshots are optional but genuinely raise conversion — a 10-second GIF of AgroGuard
detecting a diseased leaf, or the Face Attendance admin dashboard, does more work than
another badge. Record with any screen recorder, convert to a looping GIF under ~3MB
(use `gifsicle` or ezgif.com to compress), and embed with:

```markdown
![demo](assets/screenshots/agroguard-demo.gif)
```
