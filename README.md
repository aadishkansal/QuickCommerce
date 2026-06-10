# Q-Commerce Demand Forecasting & Inventory Optimization

## Overview
End-to-end demand forecasting system built on Instacart's 3.4M order dataset,
simulating dark store inventory operations (Blinkit/Zepto style).

## Key Results
- 7-day demand forecast across 5 product categories using Facebook Prophet
- Stockout risk scoring system (HIGH/MEDIUM/LOW) flagging shortages 3+ days ahead
- Market basket analysis on 30K orders — top product pairs with lift > 2.0

## Tech Stack
Python · Pandas · NumPy · Prophet · SQLite · SQL · mlxtend · Matplotlib · Seaborn

## Project Structure
data/          → Instacart CSVs (not pushed — too large)
notebooks/     → 4 Jupyter notebooks
exports/       → All charts and Excel outputs

## Dataset
Instacart Market Basket Analysis — Kaggle
3.4M orders · 32M product records · 49K products