# Supply Chain Disruption Analyzer

## Overview
A data analytics project that tracks and analyzes global supply chain 
disruptions using real Federal Reserve economic data (2018–2026).

## Live Dashboard
- Executive Summary: https://public.tableau.com/app/profile/saipriya.reddy.turpu4994/viz/Supplychaindisruptionanalyzer/SupplyChainDisruptionAnalyzer
- Detailed Analysis: [your second link here]

## Tools Used
- Python (Pandas, Matplotlib, FRED API)
- SQL / SQLite
- Tableau Public
- Jupyter Notebook

## Key Findings
- June 2022 was the peak disruption month — oil hit $114/barrel
- Automotive industry is 35% more exposed than Healthcare
- Current risk score of 72 is 3x higher than pre-COVID baseline
- COVID caused unemployment to spike from 3.5% to 14.7% in 2 months

## Data Sources
- Federal Reserve FRED API (Oil prices, PPI, CPI, Unemployment)
- Date range: January 2018 to present

## Project Structure
- `Supply chain project.ipynb` — Main Python analysis notebook
- `supply_chain_main.csv` — Processed indicators dataset
- `supply_chain_industry.csv` — Industry risk scores dataset
- `risk_score_chart.png` — Risk score visualization
- `supply_chain_overview.png` — Overview charts
