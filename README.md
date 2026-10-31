# BeautyReview.my data platform – TTTC3213 Data Engineering

Group project for TTTC3213.
# Assignment 1: Data Profiling (EDA) Report

## Team Members

- Farhan (A208766)
- Faiz (A211945)
- Khairun (A209258)

## Scenario

An online beauty retailer aims to use customer reviews and product information to identify customer sentiment and recurring concerns about makeup products. The Luxxify Makeup Dataset is suitable for this analysis because it contains real-world product and review data that may include missing values, duplicates, inconsistent formats, outliers, and rating bias. The dataset will be profiled and cleaned before being used for further analysis.

**Business Question:**  
Which makeup products receive the most negative customer feedback, and what product concerns appear most frequently in customer reviews?

## Data Source

- Dataset: Luxxify Makeup Dataset
- Source: Kaggle
- URL: (https://www.kaggle.com/datasets/zarasarkar/makeup-insights-customer-reviews)
- Files used:
  - `makeup_products.csv`
  - `makeup_reviews.csv`

The dataset was downloaded from Kaggle and loaded into a Jupyter Notebook using Pandas for data profiling and quality assessment.

## How to Run

1. Note that the dataset files are placed in `data/lake/bronze/...`.
2. Open `notebooks/gp_assignment1.ipynb`.
3. Run all cells from top to bottom.