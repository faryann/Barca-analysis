# barca-analysis — Barcelona vs Valladolid (Dec 22, 2020)

A small football analytics project that explores event/tracking-style data from the Barcelona–Valladolid match (Dec 22, 2020).  
The notebook includes basic player and passing analysis with visualizations.

![Cover](assets/cover.jpg)

## Quickstart

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook notebooks/BarC-Analysis1.ipynb
```

## Data

- `data/raw/valladolidA.csv` (included)

## What’s inside

- Filtering by team and event type
- Pass extraction and “pass network”-style summaries
- Average player positions and passing volume visualizations (via `mplsoccer`)

## Notes

- The original notebook pulled the CSV from a GitHub URL; this repo uses the local copy for reproducibility.
- Outputs are stripped for clean diffs.
