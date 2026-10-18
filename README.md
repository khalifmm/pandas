# Pandas tutorial project

This repository contains the code and data used in a Python/pandas tutorial focused on loading, inspecting, and exploring tabular data.

It includes a small Pokémon dataset and a few sample scripts that demonstrate basic pandas workflows such as reading CSV files and viewing DataFrame output.

## Contents

- `Pandas Data Science Tutorial.ipynb` — notebook with the tutorial examples
- `analysis.py` — minimal example that reads the Pokémon CSV file and prints the last rows
- `main.py` — starter script
- `pokemon_data.csv` — main dataset used in the examples
- `pokemon_data.xlsx` and `pokemon_data.txt` — alternative dataset formats

## Requirements

This project uses Python 3.12 or newer and the pandas package.

## Getting started

If you use `uv`:

```bash
uv sync
uv run python analysis.py
```

Or with plain Python:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
python -m pip install pandas
python analysis.py
```

## Notes

The tutorial video can be found here:

https://youtu.be/vmEHCJofslg

If you run into issues, the easiest way to reach out is through the video comments or by opening an issue in this repository.
