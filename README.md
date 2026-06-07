# NYC MTA Occupancy & Systemic Risk Modeling

This repository contains the project: a predictive analytics study of NYC subway occupancy, delay risk, and operational behavior using historical and real-time MTA data.

## Project overview

The project combines:
- historical turnstile usage data,
- MTA delay-causing incident records,
- live GTFS-Realtime feeds,
- and exploratory/feature-engineering workflows in Python.

The main goal is to explore how historical transit data and live train updates can be used to estimate latent passenger occupancy and system risk along the NYC subway network.

## What is in this repository

- `src/nyc-mta-occupancy-modelling.ipynb` — main analysis notebook
- `src/data/` — source CSV datasets used in the notebook
- `final_reports/main.tex` — LaTeX paper draft
- `final_reports/nyc-subway-occupancy-delay-modelling.pdf` — compiled report
- `images/` — EDA / SHAP / residual analysis visuals

## Core datasets

The notebook uses the following data sources:

1. MTA Subway Delay-Causing Incidents
2. MTA Subway Stations and Complexes
3. MTA Subway Turnstile Usage (2020–2021)
4. GTFS-Realtime feed for live train updates

## Research focus

The project investigates:
- how delay incidents vary across lines, divisions, and weekday/weekend patterns,
- how historical turnstile activity can inform crowding and occupancy proxies,
- and how live GTFS-RT signals can support real-time operational analysis.

## How to use this project

1. Open `src/nyc-mta-occupancy-modelling.ipynb` in Jupyter Notebook or VS Code.
2. Ensure the required Python packages are available (for example: pandas, matplotlib, seaborn, scikit-learn, and XGBoost if used in your environment).
3. Run the notebook cells in order to reproduce the exploratory analysis and modeling workflow.

## Report

A longer write-up of the project is available in:
- `final_reports/main.tex`
- `final_reports/nyc-subway-occupancy-delay-modelling.pdf`

## Notes

This project is intended as an academic Big Data Science proof of concept and is focused on analysis, experimentation, and interpretation rather than production deployment.
