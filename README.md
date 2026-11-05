# TaskFlow

A task-management REST API for small teams, with email reminders.

[![Built with Hexaphase](https://img.shields.io/badge/built%20with-Hexaphase-6f42c1)](https://github.com/divyekksoni/hexaphase)

A sample project built with the **Hexaphase SDLC Framework** by Divyek Soni. Mode: **Standard**.

## Status
See [project-health.md](project-health.md). Current phase: **1 – Planning**.

## Structure
```
sample-taskflow/
├── ai-instructions.md
├── project-health.md
├── 1-Planning/ … 3-Design/
├── 4-Coding/
│   ├── main-app/             ← Task REST API: users, projects, tasks (the launchable product)
│   ├── notification-worker/  ← Background worker that sends due-date reminder emails
├── 5-Testing/
└── 6-Deployment/
```

## Run
The launchable app is `4-Coding/main-app/`. Instructions are in its README once Phase 4 starts.
