# Unemployment and Inflation in Japan

## Overview

This project analyzes quarterly unemployment and inflation trends in Japan using time series modeling in R. The goal was to compare statistical models that describe each series and interpret what the results suggest about persistence, volatility, and broader macroeconomic conditions.

## Data

The data were retrieved from FRED, with original sources from the OECD. The project uses quarterly unemployment data and quarterly CPI inflation data for Japan. Inflation was annualized by multiplying the quarterly rate by four.

## Methods

The analysis follows the Box-Jenkins approach:

- Examined time series plots, ACF, and PACF
- Estimated several AR and ARMA models
- Compared model fit using AIC and BIC
- Checked residuals to evaluate model adequacy

## Key Findings

Both AIC and BIC selected an AR(2) model for unemployment, suggesting that Japan’s unemployment rate is highly persistent over time.

Both AIC and BIC selected an ARMA(1,1) model for inflation, suggesting that inflation depends on both past values and past shocks. The inflation series also showed higher volatility during the 1970s.

## Tools Used

- R
- R Markdown
- Time series analysis
- ARMA modeling
- AIC/BIC comparison
- Data visualization
