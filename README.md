# Campus Security — Guard & Admin Access Portal (Frontend Prototype)

> A frontend mockup for a campus security management system, with separate interfaces for guards and administrators.

<p align="center">
  <img src="https://img.shields.io/badge/status-early%20prototype-yellow?style=flat-square"/>
  <img src="https://img.shields.io/badge/html-100%25-orange?style=flat-square&logo=html5&logoColor=white"/>
</p>

> ⚠️ **Current state:** this repo currently contains the frontend pages only (`index.html`,
> `guard-login.html`, `guard.html`, `admin.html`) — no backend, no database, no RFID/auth logic
> committed yet. If you're showing this project in an interview or on LinkedIn, describe it
> accurately as a **UI/concept prototype for a campus access-control system**, not as a working
> RFID authentication system, until the logic layer is actually built and pushed.

## ✨ What It Does (Current Scope)

This repo lays out the **interface layer** for a campus security system with role-based views:

- `index.html` — landing/entry page
- `guard-login.html` — login screen for security guard accounts
- `guard.html` — guard-facing dashboard (presumably for logging entries/exits or flagging incidents)
- `admin.html` — administrator dashboard (presumably for managing guard accounts, viewing logs, or configuring access rules)

The role split (guard vs. admin) suggests the intended design separates **day-to-day monitoring** from **system administration** — a reasonable structure for a real access-control product, even though the logic behind both views isn't implemented yet.

## 🧠 Why I Built It

Designed as a concept for campus/smart-building security — RFID-based entry validation with guard oversight and unauthorized-entry alerting was the original idea, tying directly into coursework on authentication and access control.

## 🛠️ Tech Stack (Current)

- **Frontend:** HTML (100% of current codebase — no CSS/JS framework or backend committed yet)

## 🗺️ Roadmap — What's Needed to Make This a Real System

This is the honest next-steps list, not a finished feature set:

- [ ] Add actual authentication logic for guard/admin login (currently `guard-login.html` is presumably a static form with no backend validation)
- [ ] Implement the RFID validation logic this project was originally scoped around — either as a backend service or, if simulating without hardware, a mock validation layer
- [ ] Add a database or storage layer for guard accounts, access logs, and unauthorized-entry records
- [ ] Add CSS for actual usable styling — current pages are plain HTML
- [ ] Add a README description in GitHub's "About" section so the repo isn't unlabeled to visitors
- [ ] Once logic is added: write proper setup/run instructions here

## 📄 License

MIT (or your choice) — add a LICENSE file at repo root if missing.

---
*Built by [Rithwik K R](https://github.com/rithwikkr0)*
