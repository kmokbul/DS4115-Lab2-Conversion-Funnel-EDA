# DS 4115 Lab 2 – Conversion Funnel EDA

## Overview

This repository contains the work completed for Lab 2 of DS 4115 Marketing Analytics.

The lab focuses on Exploratory Data Analysis (EDA) and Digital Conversion Funnel Analysis using Python and Google Colab.

## Objectives

- Generate a synthetic GA4-style session dataset
- Analyze the digital conversion funnel
- Calculate conversion rates
- Identify and handle missing values
- Perform correlation analysis
- Visualize relationships using a correlation heatmap

## Funnel Stages

The conversion funnel consists of three stages:

1. Session Start
2. Add to Cart
3. Purchase

## Dataset

The synthetic dataset contains 5,000 session records and includes:

- Session ID
- User ID
- Device Category
- Session Start Flag
- Add to Cart Flag
- Purchase Flag
- Page Views
- Time on Site

## Data Cleaning

Missing values in `time_on_site_sec` were handled using median imputation.

Categorical values in `device_category` were also standardized.

## Analysis

The notebook includes:

- Dataset inspection
- Conversion funnel analysis
- Conversion rate calculation
- Missing-value detection
- Data cleaning
- Correlation matrix
- Correlation heatmap

## Files

- `Lab2_Conversion_Funnel_EDA.ipynb` – Completed Google Colab notebook
- `ga4_sample_session_logs.csv` – Generated synthetic session dataset
