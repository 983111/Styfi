# Styfi

Styfi is an AI-powered marketplace that connects small sellers directly with buyers using smart matching and AI-assisted tools like outfit recommendations, virtual try-on, and image enhancement.

This repository contains the full codebase for Styfi.

---

## Folder Structure

styfi/
├─ frontend/ # Website / UI code
├─ backend/ # APIs, database, business logic
├─ ai/ # AI systems
│ ├─ image-enhancer/
│ ├─ virtual-tryon/
│ ├─ recommender/
│ └─ trend-detector/
└─ README.md

yaml
Copy code

---

## Branching Rules

We use a simple 3-branch workflow:

- `main` → Stable / production-ready code (never commit directly)
- `dev` → Integration branch for tested features
- `feature/*` → Individual feature branches

### Rules

- Never commit directly to `main` or `dev`
- Always create a `feature/*` branch from `dev`
- One feature = one branch
- Work only inside your assigned folder
