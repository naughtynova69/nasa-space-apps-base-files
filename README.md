# AstroVitals — NASA Space Apps Challenge 2026

Base files / team context pack for **AstroVitals**, our entry for the NASA Space Apps
Challenge 2026 challenge *"Create Health Monitoring Software for Astronauts on Space
Missions"*.

AstroVitals is a real-time crew health monitoring web app for a 6-person ISS-style
mission: live vitals dashboard, clinical alert engine, per-crew trend charts, daily
health reports, and a demo scenario injector (fever, hypoxia, radiation storm...).

**Stack:** TypeScript everywhere — React 18 + Vite + Tailwind + Recharts + Socket.IO
on the frontend, Node.js + Express + Socket.IO on the backend. All telemetry is
simulated (no real medical data, no API keys).

## Files

Read in order:

| File | Contents |
|------|----------|
| [00_READ_ME_FIRST.txt](00_READ_ME_FIRST.txt) | Orientation — start here |
| [01_PROJECT_CONTEXT.txt](01_PROJECT_CONTEXT.txt) | What we're building and why (the pitch) |
| [02_CHALLENGE_BRIEF.txt](02_CHALLENGE_BRIEF.txt) | The official Space Apps challenge, decoded |
| [03_ARCHITECTURE.txt](03_ARCHITECTURE.txt) | System architecture, module by module |
| [04_API_REFERENCE.txt](04_API_REFERENCE.txt) | Every REST endpoint + socket event |
| [05_DATA_DICTIONARY.txt](05_DATA_DICTIONARY.txt) | Every metric, unit, threshold (clinical model) |
| [06_SETUP_GUIDE.txt](06_SETUP_GUIDE.txt) | Get it running on Windows/macOS/Linux |
| [07_GIT_WORKFLOW.txt](07_GIT_WORKFLOW.txt) | Branches, commits, PR rules |
| [08_TASK_BOARD.txt](08_TASK_BOARD.txt) | Prioritized tasks you can claim today |
| [09_FOLDER_STRUCTURE.txt](09_FOLDER_STRUCTURE.txt) | Every file in the app repo and what it does |
| [10_DESIGN_SYSTEM.txt](10_DESIGN_SYSTEM.txt) | UI theme, colors, component patterns |
| [11_FAQ_GLOSSARY.txt](11_FAQ_GLOSSARY.txt) | Quick answers + space-medicine vocabulary |
| [12_SESSION_LOG.txt](12_SESSION_LOG.txt) | Work log: what was done on the pack + app repo, newest last |

## Quick start

Clone the main app repo, then:

```bash
npm install
npm run dev
# -> open http://localhost:5173
```

Scripted demo events start firing within ~4 minutes (fever at 4 min, dehydration at
10 min, radiation storm at 16 min).

---
Pack generated 2026-11-13 · repo v1.0.0
