# Time Series Forecasting Project

This project focuses on time series forecasting using different techniques. The goal is to illustrate why Simple Exponential Smoothing (SES) may not be suitable for certain types of time series data and why alternatives like Holt-Winters are more appropriate.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Time series data often exhibits various patterns, including trends and seasonality. This project explores the limitations of using Simple Exponential Smoothing (SES) for time series forecasting when the data possesses specific characteristics such as an upward trend and seasonality.

### Reasons for Not Using SES
1. **Upward Trend**: SES is unsuitable for data with clear trends, as it assumes stationary data.
2. **Inability to Capture Changing Trends**: SES assigns equal weight to all prior observations, making it ineffective for changing trends.
3. **Inability to Capture Seasonality**: SES doesn't account for seasonality in the data.
4. **Stability**: SES forecasts can be unstable when dealing with outliers or extreme values.
5. **Holt-Winters**: The Holt-Winters method is recommended for forecasting time series data with both trends and seasonality.

## Project Structure

