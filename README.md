Exploratory Analysis of Diphtheria in the US (1888–1981)


This project explores historical mortality trends of diphtheria in the United States from 1888 to 1981 using the Project Tycho dataset. The analysis combines data cleaning, visualization, changepoint detection, interrupted time series regression, and ARIMA forecasting to understand the impact of vaccination campaigns.

Features

Data Preparation

Loading and cleaning diphtheria mortality data.

Aggregation by year, month, city, and state.

Visualization

Yearly deaths trend line.

Monthly seasonality boxplots.

LOESS smoothing of time series.

STL decomposition into trend, seasonal, and residual components.

Bar plots of top 10 cities and states.

Choropleth mapping of average deaths by state.

Modeling

Changepoint detection using the PELT algorithm.

Interrupted time series regression to estimate the vaccination effect.

ARIMA forecasting to project counterfactual trends.

Outputs

Cleaned datasets and summary tables.

Figures saved as PNG files.

Figures and Tables
This analysis produces:

Figures

Yearly diphtheria deaths (1888–1981)

Top 10 cities with the highest deaths

Monthly seasonality boxplot

LOESS smoothed trend

STL decomposition

Changepoint detection plot

Interrupted time series regression plot

ARIMA forecast plot

Top 10 states bar chart

Choropleth map of state-level mortality

Tables

Summary statistics

Yearly deaths by state

Top 10 states by total deaths

These are saved in the figures/ and tables/ directories.

Dependencies
R >= 4.0

dplyr

ggplot2

lubridate

changepoint

forecast

ggthemes

tmap

sf

readr

zoo













