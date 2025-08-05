# Brent Oil Price Modeling

> Bayesian Change Point Detection & Statistical Analysis on Brent Oil Prices

## 📌 Overview

This project investigates how major geopolitical and economic events affect Brent oil prices using Bayesian change point analysis. The aim is to identify structural breaks in the price series and associate them with real-world events, providing insights for investors, policymakers, and energy companies.

## 🧠 Business Objective

Conduct statistical modeling on Brent oil prices to:
- Detect change points using Bayesian inference.
- Associate price shifts with historical events (e.g., OPEC decisions, wars, sanctions).
- Quantify the impact of these events on price behavior.

## 🗂️ Project Structure

```bash
brent-oil-price-modeling/
│
├── data/                  # Raw and cleaned datasets
├── notebooks/             # Jupyter notebooks for EDA and modeling
├── src/                   # Source code (models, utilities)
├── reports/               # Interim and final reports
├── dashboard/             # Flask + React dashboard (Task 3)
├── events/                # CSV or JSON with key historical events
├── README.md              # Project overview
└── requirements.txt       # Python dependencies
