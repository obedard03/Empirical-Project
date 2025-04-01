# UK Cost of Living Analysis

## Overview
This project analyzes how the cost of living in the UK has changed over time using ONS inflation data and supermarket essential prices.

## Steps to Run
1. Clone the repo and install packages:
```sh
pip install -r requirements.txt
```
2. Download ONS CPI CSV and place in `data/raw/`
3. Run:
```sh
python src/scrape_supermarket.py
python src/load_ons_data.py
python src/merge_analysis.py
```
4. Open `notebooks/blog.ipynb` for blog post

## Project Structure
- `data/` — includes ONS and scraped product data
- `output/` — plots and final summaries
- `src/` — all data scripts
- `notebooks/` — main analysis and write-up
"""
