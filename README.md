# Statistics with Python — Bike Sharing Capstone

**Research question:** What drives bike-sharing demand, and how do those drivers change across working status, time of day, season, weather, and rider type?

Data: UCI Bike Sharing Dataset (Capital Bikeshare, Washington D.C., 2011–2012), hourly (`hour.csv`) and daily (`day.csv`).

## Dataset freeze
- `00_freeze.ipynb` cleans both raw files once and writes `data/clean.csv` (hourly) and `data/clean_day.csv` (daily). Those stay local.
- `freeze_receipt.json` records row counts, columns, and SHA-256 fingerprints of the raw and clean files.
- `data/sample_10k.csv` is a 10,000-row random sample (`random_state=42`) of the hourly clean file.

To reproduce: put `hour.csv` and `day.csv` next to the notebook and Run All.
