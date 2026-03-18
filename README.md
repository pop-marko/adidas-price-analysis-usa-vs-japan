# Price Comparison: Adidas US vs Japan

## Overview
This project analyzes price differences for Adidas running shoes between the US and Japan markets by comparing identical models across both regions.

## Goal
Identify which market offers lower prices for the same products and highlight potential pricing gaps.

## Data
- Source: https://www.kaggle.com/datasets/bsthere/adidas-global-catalogue-2026?select=Adidas_Global.csv
- Files used:
  - US_Adidas.csv
  - JP_Adidas.csv

## Methodology
- Data cleaning and filtering (running category only)
- Currency conversion (JPY to USD)
- Dataset merging using model_number

## Results
- Products are matched using model_number
- Prices are normalized to USD for comparison
- Duplicate entries are removed
- Price differences are calculated for each product
- A visualization compares prices across markets
