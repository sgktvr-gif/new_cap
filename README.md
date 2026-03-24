# README.md
# new_cap

Meeting Intelligence & Context Agent Project Scaffold

This project is a production-ready Python FastAPI-based backend, Dockerized for local and cloud deployment. See docs/PRD.md for requirements.

## Local Setup (Docker)

1. Clone this repo:
   git clone https://github.com/sgktvr-gif/new_cap.git
   cd new_cap
2. Copy .env.example to .env and supply secrets as needed (see below)
3. Start development environment:
   docker-compose up --build

## API Access
App launches FastAPI at http://localhost:8000 by default.

## Project layout:
- app/: All FastAPI backend code
- docs/: Documentation (PRD, design, API, etc.)
- tests/: Automated tests

## Next steps
- See docs/PRD.md for full product plan.
- Integrations (Google, Zoom, Slack) coming soon.
