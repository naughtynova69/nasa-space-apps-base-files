================================================================================
 ASTROVITALS - TEAM CONTEXT PACK
 NASA Space Apps Challenge 2026
 Challenge: "Create Health Monitoring Software for Astronauts on Space Missions"
================================================================================

 READ THIS FILE FIRST

--------------------------------------------------------------------------------
 WHAT THIS PACK IS
--------------------------------------------------------------------------------

This folder is a complete, self-contained briefing for every teammate joining
the AstroVitals project. It was generated so that you can contribute WITHOUT
needing a walkthrough call. Read the files in order:

  00_READ_ME_FIRST.txt      <- you are here: orientation
  01_PROJECT_CONTEXT.txt    <- what we are building and why (the pitch)
  02_CHALLENGE_BRIEF.txt    <- the official Space Apps challenge, decoded
  03_ARCHITECTURE.txt       <- how the system works, module by module
  04_API_REFERENCE.txt      <- every REST endpoint + socket event
  05_DATA_DICTIONARY.txt    <- every metric, unit, threshold (clinical model)
  06_SETUP_GUIDE.txt        <- get it running on Windows/macOS/Linux
  07_GIT_WORKFLOW.txt       <- branches, commits, PR rules, commands to copy
  08_TASK_BOARD.txt         <- prioritized tasks you can claim TODAY
  09_FOLDER_STRUCTURE.txt   <- every file in the repo and what it does
  10_DESIGN_SYSTEM.txt      <- UI theme, colors, component patterns
  11_FAQ_GLOSSARY.txt       <- quick answers + space-medicine vocabulary

--------------------------------------------------------------------------------
 THE 60-SECOND VERSION
--------------------------------------------------------------------------------

PROJECT:   AstroVitals - a real-time crew health monitoring web app for a
           6-person ISS-style mission. Live vitals dashboard, clinical alert
           engine, per-crew trend charts, daily health reports, and a demo
           scenario injector (fever, hypoxia, radiation storm...).

STACK:     TypeScript everywhere.
           Frontend: React 18 + Vite + Tailwind CSS + Recharts + socket.io-client
           Backend:  Node.js + Express + Socket.IO (no database needed for v1)

REPO:      https://github.com/Avani376/astronaut-health-monitoring
OWNER:     Avani (https://github.com/Avani376)

RUN IT:    git clone the repo, then:
             npm install
             npm run dev
           -> open http://localhost:5173
           Within ~4 minutes scripted demo events start firing (fever at
           4 min, dehydration at 10 min, radiation storm at 16 min).

DATA:      ALL telemetry is SIMULATED (a physiologic model runs at 1 Hz on the
           server). No real medical data, no API keys, no NASA credentials.

YOUR MOVE: Read 06 (setup) and 08 (task board) first if you want to start
           coding immediately. Everything else is reference material.

--------------------------------------------------------------------------------
 CONTACT / OWNERSHIP
--------------------------------------------------------------------------------

- Repo owner / team lead: Avani (Avani376 on GitHub)
- Claim tasks by commenting on the issue/PR - see 07_GIT_WORKFLOW.txt
- Questions not covered by this pack: ask in the team chat; update the FAQ
  file (11) with the answer so the next person benefits.

                                        -- Pack generated 2026-11-13, repo v1.0.0
================================================================================
