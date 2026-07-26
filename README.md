# Mastermind

A Jupyter notebook implementing the classic Mastermind code-breaking game:

- **Play it yourself** — guess a secret 4-peg code (from 6 colors) and get black/white peg feedback.
- **Auto-solver** — an implementation of Knuth's minimax strategy, which solves any secret code in at most 5 guesses.

## Setup

A local virtual environment is included in `.venv/` (not committed to git). To recreate it:

```
python -m venv .venv
.venv\Scripts\pip install ipykernel
.venv\Scripts\python -m ipykernel install --user --name mastermind --display-name "Python (mastermind)"
```

Then open `mastermind.ipynb` and select the **Python (mastermind)** kernel.
