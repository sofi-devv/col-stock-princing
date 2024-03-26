# Stock Trend Analysis for Ecopetrol

## Objective

The goal of this project is to determine whether the trend in Ecopetrol's stock price correlates with the sentiment (positive, negative, or neutral) of related news articles.

## Data Extraction

### Stock Data

- The national price data for Ecopetrol was extracted from Grupo Aval's financial portal, which provides historical data on Colombian stock market activities. The extraction process is detailed in a Colab notebook found within the `stock` folder.
  - Source: [Grupo Aval - Historical Data](https://www.grupoaval.com/wps/portal/grupo-aval/aval/portal-financiero/renta-variable/acciones-bolsa-colombia/datos-historicos)
  
- The international data was obtained using the Yahoo Finance API, showcasing the stock's performance in a global context.

### News Data

- The `newsWebScraping` folder contains the extraction process of news articles related to Ecopetrol, sourced from "La Prepublica". This process captures the sentiment trends from the news and attempts to correlate it with the stock price movements.

## Data Organization

Within the project, you will find the following directory structure:

- `not-normalized/`: Contains raw CSV files of stock prices for Colombia (`Col`) and the USA without any normalization.
- `normalized/`: Contains CSV files of stock prices that have been normalized for direct comparison.

Each folder includes two CSVs corresponding to the Colombian and US markets under different conditions.

## Analysis

The subsequent analysis aims to visually and statistically identify patterns or correlations between the stock price movements and news sentiments.

## How to Use

1. Clone the repository to your local machine.
2. Navigate to the `stock` folder to view the Colab notebook for detailed data extraction steps.
3. Access the `not-normalized` or `normalized` folders to view or use the stock price data.
4. Review the `newsWebScraping` folder for the news extraction methodology and data.


