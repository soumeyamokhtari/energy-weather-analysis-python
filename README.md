#  Weather Impact on Energy Consumption and Production (Python)
## Project Overview

This project explores how weather variables such as temperature, humidity, and solar irradiance (GHI) influence energy consumption and production patterns across different times of the day and seasons.

The analysis is based on hourly data and focuses on exploratory data analysis (EDA), correlation analysis, and a simple predictive model to understand combined effects, rather than formal hypothesis testing.

## Dataset

Source: Public energy and weather dataset (Kaggle)

Observations: Hourly data (2017–2022)

Key variables include:

Energy delta (Wh)

Temperature

Humidity

Global Horizontal Irradiance (GHI)

Sunlight indicators (isSun, sunlightTime)

Time features (hour, month, season)

## Objectives

The project aims to:

Identify daily and seasonal patterns in energy consumption and production

Examine relationships between energy delta and weather conditions

Analyse the combined influence of multiple weather variables

Demonstrate a basic predictive approach using weather features

## Methodology

The analysis follows these steps:

Data Preparation

Datetime parsing and feature extraction (hour, month, season)

Selection of relevant weather and energy variables

Exploratory Data Analysis

Energy patterns by hour of the day

Energy patterns by season

Relationships between energy delta and key weather variables

Correlation Analysis

Assessment of linear relationships between weather features and energy delta

Predictive Modelling

Linear regression model to estimate energy delta

Model evaluation using Mean Absolute Error (MAE)

## Key Findings

Energy delta shows clear daily and seasonal variations

Solar irradiance (GHI) and sunlight-related features are strongly associated with changes in energy production

Temperature and humidity also influence energy patterns, though to a lesser extent

A simple regression model demonstrates that weather variables can partially explain energy variability

## Tools and Technologies

Python

pandas

matplotlib

seaborn

scikit-learn

## How to Run

Open the notebook located in the notebooks folder

Run all cells sequentially in Google Colab or Jupyter Notebook

## Notes

This repository represents a portfolio-oriented version of an academic project, adapted from an initial SPSS analysis to a transparent and reproducible Python workflow.

## Author

Soumeya Mokhtari
MSc Big Data & Data Science
