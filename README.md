# Cross-Calibration-Analysis
This repository contains the code used in my master's thesis for cross-calibrating solar energetic particle (SEP) data from the SOHO/ERNE and IMP-8/GME instruments.

## Project Summary

The goal was to improve measurement consistency between two satellite instruments observing SEP events. The analysis includes:
- Data preprocessing and cleaning
- Visual inspection and event segmentation
- RANSAC regression, χ²-fitting, and optimization using ORDin

## Contents

- `notebooks`: Jupyter notebook with full analysis and the HTML version which you can look at whitout running any code
- `data`: The data needed for the analysis can be found on Google Drive: https://drive.google.com/drive/folders/1E-sVoM8nu9m4--gEreiudJAxJe33LQQ2?usp=drive_link

## Libraries used

- Python 3.10+
- `pandas`, `numpy`, `matplotlib`
- `scikit-learn`, `statsmodels`, `scipy.odr`

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook Ville_antila_Notebook.ipynb
