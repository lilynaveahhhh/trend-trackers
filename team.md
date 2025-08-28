# Samsung EnnovateX 2025 AI Challenge Submission

## Problem Statement
On device agentiic system for intelligent battery optimization 

## Team Name
<Your Trend Trackers>

## Team Members
- Tisha
- Shruti
- Suryansh
- Manav

## Project Artefacts

### Technical Documentation - Docs
All technical details are written in markdown files inside the `src` folder in the repo.

#### Structure:
- `src/approach.md` – Solution approach and uniqueness
- `src/stack.md` – Technical stack and OSS libraries
- `src/architecture.md` – Technical architecture diagram and explanation
- `src/installation.md` – Installation instructions
- `src/user-guide.md` – User guide and screenshots
- `src/features.md` – Salient features

### Source Code - Source
All source code is in the `client/src` and `server/` folders. The code is installable and executable on supported platform
---

# Approach

Our solution provides real-time system monitoring and AI-powered optimization for consumer devices. It features a dashboard for live metrics, automated resource management, and intelligent suggestions. The architecture is modular, scalable, and uses modern web technologies for both frontend and backend.

# Technical Stack
- **Frontend:** React, Vite, Tailwind CSS, shadcn/ui, TanStack Query, Wouter
- **Backend:** Express.js, TypeScript, WebSocket, Drizzle ORM
- **Database:** PostgreSQL (via Drizzle ORM)
- **Other OSS Libraries:**
  - [React](https://react.dev/)
  - [Vite](https://vitejs.dev/)
  - [Tailwind CSS](https://tailwindcss.com/)
  - [Drizzle ORM](https://orm.drizzle.team/)
  - [shadcn/ui](https://ui.shadcn.com/)
  - [systeminformation](https://github.com/sebhildebrandt/systeminformation)

# Architecture
- **Client:** Modular UI components for monitoring and control
- **Server:** REST API and WebSocket for real-time updates
- **Shared:** Schema definitions for type safety

# Installation Instructions
```bash
git clone <repo-url>
cd NexusBoost
npm install
npm run dev
```

# User Guide
- Access dashboard at `http://localhost:5000`
- Use system vitals, AI optimization, and network monitoring features
- Real-time updates via WebSocket

# Features
- AI Optimization
- Biometric Cooling
- CPU & Network Monitoring
- Real-time System Vitals
- Modern UI

---


# Attribution
Project built from scratch. If any OSS project is used as a base, mention here.
