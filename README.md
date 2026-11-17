# Rainfall Analysis and Planting Advisory

A farmer-support NGO sends SMS advice on planting windows to farmers in five counties (Nairobi, Nakuru, Kisumu, Mombasa and Machakos). This project cleans a hand-typed Machakos rainfall record, combines it with four clean county records, analyses monthly rainfall with NumPy and produces a short planting advisory for each county.

## Files

| File | Purpose |
|------|---------|
| `rainfall_analysis.ipynb` | Cleaning, NumPy analysis, planting advisory and data-quality notes (all outputs saved) |
| `rainfall_summary.csv` | One row per county: `county`, `annual_total_mm`, `wettest_month`, `dry_months`, `planting_window` |
| `requirements.txt` | Python libraries needed to run the notebook |

## How to run the notebook

1. Install the requirements: `pip install -r requirements.txt`
2. Start Jupyter: `jupyter notebook rainfall_analysis.ipynb`
3. Choose **Kernel > Restart & Run All**. The notebook recreates `rainfall_summary.csv` in the same folder.

## Planting advisory

- Farmers in Nairobi, Nakuru, Kisumu and Mombasa should plant in April–May, when the two wettest consecutive months bring 265 mm to 420 mm of rain.
- Machakos farmers should wait for the short rains and plant in November–December (278 mm), the wettest two-month stretch in that county.
- Treat Machakos figures as estimates, because its April and September readings were unreadable and were filled with a 68 mm average, so confirm the start of the rains with a local forecast before sowing.
