# AGENTS.md

Notes for working in this repo (me or an assistant).

## Shape

- I add folders as I go through the course; nothing is pre-created.
- Top level: flat topic folders (`search`, `knowledge`, `uncertainty`, `optimization`, `learning`, `neural-networks`, `language`).
- Under each topic: one folder per project. Names follow the course when possible.
- Each new topic or project folder gets a short `README.md` (what it is, how to run).

Topic and project list: root `README.md`.

## Rules

- Edit only the folder I'm working on unless I say otherwise.
- No secrets, large datasets, or model weights in git (see `.gitignore`).
- Respect CS50 academic integrity for anything I submit.
- Do not scaffold the full tree unless I ask.

## Environment

Python 3.10+. Optional venv at repo root:

```bash
python3 -m venv .venv && source .venv/bin/activate
```

Dependencies come from each project's distribution, not a shared setup yet.

## Links

Course projects: [CS50 AI projects](https://cs50.harvard.edu/ai/projects/).
