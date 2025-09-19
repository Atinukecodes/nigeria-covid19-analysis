# nigeria-covid19-analysis
COVID-19 analysis for Nigerian states
# Nigeria COVID-19 Analysis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview
This project analyzes COVID-19 data across Nigerian states using data cleaning and Exploratory Data Analysis (EDA). It includes validation, derived metrics (e.g., mortality/recovery rates), visualizations (bar charts, heatmaps, box plots, interactive map), and hypothesis testing to explore regional disparities.

## Dataset
- Source: `naija_data.csv` (cumulative cases by state, including confirmed, active, discharged, deaths, lat/long).
- Rows: 37 (one per state/FCT).

## Key Insights
- Lagos leads with ~101k cases due to population density.
- Mortality ~2.3%, recovery ~97%; outliers in low-case states.
- No significant north-south mortality difference (p=0.626).

## Visualizations
![Top 10 States](top_10_states.png)
![Rate Distribution](boxplot.png)
(Interactive map: Open `nigeria_covid_map.html`.)

## Setup and Usage
1. Clone: `git clone https://github.com/yourusername/nigeria-covid-analysis.git`
2. Install: `pip install -r requirements.txt`
3. Run: `jupyter notebook nigeria_covid_eda.ipynb`

## Technologies
- Python: Pandas, NumPy, Seaborn, Matplotlib, Folium, SciPy.
- Environment: Jupyter Notebook / Google Colab.

## Future Work
- Add population data for per-capita rates.
- Explore ML predictions.

## License
MIT License - Free to use!

Author: Atinuke Towoju | Date: 19th September 2025
