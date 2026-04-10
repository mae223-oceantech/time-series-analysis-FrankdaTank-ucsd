# MAE223 — Time Series Analysis (Week 1 Lab)

## Overview
UCSD MAE223 course lab on time series analysis. Students work through Jupyter notebooks covering power spectral density, Welch's method, tidal analysis, and ocean wave data from the SAFARI 2025–2026 field campaign.

## Stack
- Python 3.11, Jupyter notebooks (.ipynb)
- NumPy, SciPy, Matplotlib
- Conda environment: `mae223`

## Environment setup
```bash
conda env create -f environment.yml
conda activate mae223
python -m ipykernel install --user --name mae223 --display-name "mae223"
```

## Notebooks (work in order)
1. `Tidal Analysis_Python.ipynb` — demo, fully written, run and read only
2. `Tutorial_SpectralAnalysis.ipynb` — student fills in `# YOUR CODE HERE` cells
3. `Tutorial_SAFARI_SST.ipynb` — SAFARI sea surface temperature analysis

## Key data files
- `sample_data.json` — CLASS10 mooring velocity time series (30-min, 16k samples)
- `la_jolla_tide.json` — NOAA La Jolla tide gauge (~100-year record, hourly, mm)
- `safari_waves.json` — SAFARI buoy significant wave height (central Pacific, irregular ~2-hr sampling)
- `safari_sst.json` — SAFARI sea surface temperature data

## Conventions
- Cells marked `# YOUR CODE HERE` are where student code goes
- Reflection question answers go in the provided answer cells below each question
- Run cells top to bottom; use Run All to avoid NameErrors
- Do not modify the demo notebook (`Tidal Analysis_Python.ipynb`)

## Submission
Lab reports submitted via Canvas, not GitHub. Push notebook progress to GitHub for backup.
