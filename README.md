# Cody Ostler

**Data applications · API integrations · Applied AI**

I build software that connects data, services, and useful interfaces—from MLB analytics to connected-vehicle experiences and everyday tools. I'm pursuing a master's degree in Applied Artificial Intelligence at Utah Valley University, with a background in data analysis and Information Systems focused on Business Intelligence.

I'm working toward hands-on roles in applied AI, data applications, and integration engineering. The projects below show the software, technical decisions, and testing behind that work.

## Selected work

### 1. Baseball App — data pipelines and interactive analytics

An MLB dashboard combining scheduled Python data jobs, public APIs, live game views, and a 3D ball-flight visualization. The fantasy projection component includes an explicit evaluation plan and documented limitations.

**Python · FastAPI · React · Three.js · GitHub Actions**  
[Try the dashboard](https://codyglenostler.github.io/baseball-app/) · [Explore the code](https://github.com/codyglenostler/baseball-app) · [Engineering decisions](https://github.com/codyglenostler/baseball-app#engineering-decisions) · [Model evaluation](https://github.com/codyglenostler/baseball-app/blob/main/docs/MODEL_EVALUATION.md)

### 2. Ludic Pulse Web — browser integrations and privacy

The public website and browser clients for a Tesla companion product. Its Shared ETA client handles time-limited trip links, token handoff, route selection, and network failure states. The case study connects those constraints to implementation and tests.

**JavaScript · Web Workers · Apple MapKit JS · Vercel**  
[Visit the website](https://ludicpulse.com) · [Explore the code](https://github.com/codyglenostler/ludicpulse-web) · [Read the Shared ETA case study](https://github.com/codyglenostler/ludicpulse-web/blob/main/docs/SHARED_ETA_CASE_STUDY.md)

### 3. Workout Tracker — practical product and storage design

A mobile workout log with browser-local storage, completed-workout history, and optional cloud backup and restore. Its documentation explains offline behavior, queued writes, and the limits of synchronization across devices.

**TypeScript · Next.js · IndexedDB · Dexie · Supabase**  
[Try the app](https://workout-tracker-two-beta.vercel.app) · [Explore the code](https://github.com/codyglenostler/workout-tracker) · [Storage decisions](https://github.com/codyglenostler/workout-tracker#engineering-decisions)

## What I'm working on

- **Applied AI evaluation:** chronological holdouts, meaningful baselines, and reproducible results for the baseball projection work.
- **Reliable integrations:** explicit failure states, data freshness, and clear boundaries between browser clients and external services.
- **Useful products:** focused workflows that can be tried, inspected, and explained.

## About these projects

These are personal projects developed with AI coding assistance. Each featured repository includes a walkthrough, architecture, source map, setup instructions, and known limitations. The public Ludic Pulse repository covers the website and browser clients; the iPhone app and cloud API are separate. Baseball projections remain experimental, and Workout Tracker's cloud feature is optional backup and restore.
