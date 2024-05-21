# Forecasting Bike Share Usage in Chicago

## Introduction

The primary objective of this project is to accurately predict the demand for Divvy bikes in Chicago using historical trip data provided by the company. By analyzing patterns in bike usage, the project aims to enhance the availability and efficiency of bike-sharing services for Divvy customers. The project will employ various time series forecasting models, including SARIMA, Prophet, Orbit, and LSTM, to predict the demand for both classic and electronic bikes. This predictive analysis will enable Divvy to optimize its bike stock management across different periods, thereby reducing operational costs and improving customer access to bikes during peak demand times.

## Chicago Divvy Bicycle Dataset

The dataset provided by Divvy includes historical trip data that is publicly available for various uses, including analysis and forecasting. The data is released on a monthly schedule and adheres to the Divvy Data License Agreement. Each record in the dataset is anonymized for privacy and includes several key features:

 * **Trip Start Day and Time**: The date and time when the bike trip started.
 * **Trip End Day and Time**: The date and time when the bike trip ended.
 * **Trip Start Station**: The station where the bike trip began.
 * **Trip End Station**: The station where the bike trip concluded.
 * **Rider Type**: The category of the rider, which includes Member, Single Ride, and Day Pass.
 * Download the data directly from: https://divvybikes.com/system-data
