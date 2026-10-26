
# RACC — Road Accident Analysis Dashboard

A Streamlit dashboard for analyzing road accident records through
data cleaning, exploratory data analysis, classification, prediction,
and monthly forecasting.

## Features

- CSV upload and data-quality checks
- Statistical analysis and exploratory data analysis
- Injury severity classification
- Daily accident-record prediction
- Monthly forecasting
- CSV and ZIP downloads

## Requirements

Python 3.10 or compatible with the installed package versions.

## Installation

```bash
pip install -r requirements.txt
```

## Run the application

```bash
python -m streamlit run racc_streamlit_app.py
```

## Project files

- `racc_streamlit_app.py` — Main Streamlit dashboard
- `part_2_data.py` — Data preparation and statistics
- `part_3_models.py` — Machine-learning models
- `part_4_results.py` — Forecasting and result downloads
- `requirements.txt` — Required Python packages
- `style.css` — Optional dashboard styling
