# NYC Crash Severity Prediction

This repository contains a reproducible logistic-regression analysis of injury severity for New York City crashes from June 30 through July 6, 2024.

## Repository layout

- `homework6.qmd` - source analysis
- `homework6.pdf` - rendered report
- `data/nyc_crashes_2024-06-30_to_2024-07-06.csv` - model input

## Run locally

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
quarto render homework6.qmd
```

Quarto and a PDF engine such as Tectonic must be installed separately.

## Data source

The input was downloaded on September 23, 2026 from NYC Open Data's [Motor Vehicle Collisions - Crashes](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95) dataset. The dataset is revised over time, so row counts can differ from older rendered reports.
