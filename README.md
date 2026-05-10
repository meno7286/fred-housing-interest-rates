# Interest Rates and Housing Market Activity in the United States

## Project Overview

This project looks at the relationship between interest rates and housing market activity in the United States. The analysis uses monthly data from the Federal Reserve Economic Data (FRED) database, including the Federal Funds Rate, housing starts, and building permits.

The goal of this project is to find out whether interest rates are associated with changes in housing market activity and to better understand how these variables move together over time.

## Research Question

What is the relationship between interest rates and housing market activity in the United States?

## Hypothesis

H0: There is no relationship between interest rates and housing market activity.

H1: There is a relationship between interest rates and housing market activity.


## Data

The project uses three datasets from FRED:

FEDFUNDS: Federal Funds Rate
HOUST: Housing Starts
PERMIT: Building Permits

The data contains monthly observations from March 2000 - March 2026.

## Methods

This analysis includes:

- Data cleaning 
- Summary statistics
- Distribution plots
- Time series visuals
- Scatterplots
- Correlation analysis
- High rate and low rate period comparison
- Linear Regression

## Key Findings

The EDA and regression indicate a positive relationship between interest rates and housing market activity during our sample period. Both housing starts and building permits are positively associated with the Fed Funds Rate.

However, my regression models had low R squared values, meaning interest rates explain only part of the variation in housing activity. I believe that other economic factors also play an important role.

We reject the Null.

## Limitations

This project uses time series data, so the results should not be interpreted as because of causation. Other economic factors were not included in the regression.

