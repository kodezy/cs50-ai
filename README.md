# cs50-ai

Personal workspace for [CS50's Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/): labs, starter code, notes, and experiments. Not affiliated with Harvard CS50.

## Layout

Create folders only as you work through the course. Suggested top-level names (flat, one topic per folder):

| Folder | Topic | Example projects |
| --- | --- | --- |
| `search/` | Search | `degrees`, `tictactoe` |
| `knowledge/` | Knowledge | `knights`, `minesweeper` |
| `uncertainty/` | Uncertainty | `pagerank`, `heredity` |
| `optimization/` | Optimization | `crossword` |
| `learning/` | Learning | `shopping`, `nim` |
| `neural-networks/` | Neural networks | `traffic` |
| `language/` | Language | `parser`, `questions` |

Under each topic folder, one subfolder per project is enough. Keep distributions, your code, and small notes there. When you add a topic or project folder, add a short `README.md` in that folder (what it is, how to run).

Course write-ups: [CS50 AI projects](https://cs50.harvard.edu/ai/projects/).

## Setup

Python 3.10+ (match the version you use for edX if you submit). Optional venv at the repo root:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install dependencies per project (each distribution lists its own packages). You may add a root `requirements.txt` later if you want one shared pin file.

Keep secrets and large generated files out of git (see `.gitignore`).

## Usage

Work from the project folder you create. Follow the run and submit steps in the official project spec. Use `check50` and `submit50` when you submit through the course.

How I extend this repo: `AGENTS.md`.
