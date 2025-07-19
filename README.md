# Cross-Calibration-Analysis
This repository contains the code used in my master's thesis for cross-calibrating solar energetic particle (SEP) data from the SOHO/ERNE and IMP-8/GME instruments.

## Project Summary

The goal was to improve measurement consistency between two satellite instruments observing SEP events. The analysis includes:
- Data preprocessing and cleaning
- Visual inspection and event segmentation
- RANSAC regression, χ²-fitting, and optimization using ORDin

## Structure

- `notebooks/`: Jupyter notebook with full analysis
- `data/`: Data needed for the analysis

## Libraries used

- Python 3.10+
- `pandas`, `numpy`, `matplotlib`
- `scikit-learn`, `statsmodels`, `scipy.odr`

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebooks/crosscalibration.ipynb
