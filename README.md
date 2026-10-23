# Kenya Maize Yield Analysis

A data analysis project exploring maize yield trends in Kenya from 1961 to 2024, using rainfall data from NASA POWER to assess the relationship between precipitation and crop productivity.

## Overview

This repository includes:
- `Maize_produce_1961-2024.csv` — maize yield data for Kenya
- `Nasa_rainfall.csv` — rainfall data
- `maize_yield.ipynb` — Jupyter Notebook containing the full analysis

## Objectives

- Analyze historical maize yield trends in Kenya
- Compare yield changes across decades
- Explore the relationship between rainfall and maize output
- Build a simple regression model to assess predictive patterns

## Data Sources

- Maize yield: FAOSTAT
- Rainfall: NASA POWER

## Tools Used

- Python
- pandas
- matplotlib
- NumPy
- scikit-learn
- Jupyter Notebook

## Key Findings

- Maize yield in Kenya shows clear long-term fluctuations across the study period.
- The 1980s and early 1990s recorded some of the highest average yields.
- Yield dropped sharply in several years, suggesting climate and agricultural variability.
- Annual rainfall and yield show a positive relationship, though the correlation is moderate.
- A simple linear regression model was used to evaluate rainfall as a predictor of yield performance.

## How to Run

```bash
git clone https://github.com/wandia-123/kenya-maize-yield-analysis.git
cd kenya-maize-yield-analysis
pip install pandas matplotlib numpy scikit-learn jupyterlab
jupyter lab
