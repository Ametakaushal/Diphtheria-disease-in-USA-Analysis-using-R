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

License
This project is licensed under the MIT License.

If you like, I can tailor it further or help you add badges or usage examples.








You said:
can i copy paste it directly?


ChatGPT said:
✅ Yes—absolutely!

You can copy-paste the entire text I shared directly into a README.md file in your GitHub repository—no changes needed unless you want to:

Update the Git clone URL to your actual repository link (https://github.com/your-username/diphtheria-analysis.git)

Add or remove sections (e.g., License, Dependencies)

Quick steps to do this:

Create a new file called README.md in your repo root folder.

Paste the text I gave you.

Save and commit.
