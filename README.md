## Financial Market Analysis Notebook

## Project Description

This Jupyter notebook offers a comprehensive analysis of financial markets, specifically focusing on the S&P 500 index, WTI crude oil, and spot gold prices. It demonstrates fetching historical market data, data preprocessing, interactive visualization, and forecasting future market trends using advanced time series models.

## Built With

Visual Studio Code - The source code editor used for development.

GitHub Copilot - AI assistant that helps in writing better code.

ChatGPT - AI model for generating documentation and guidance.

# Installation Instructions

## Prerequisites
Python 3.6 or higher
Pip package manager
Libraries

## The following Python libraries are required:

pandas: for data manipulation and analysis.

hvplot: for creating interactive plots.

prophet: for time series forecasting.

yfinance: for downloading historical market data.

## Installation
To install the required libraries, run the following command in your terminal:

bash

Copy code

pip install pandas hvplot prophet yfinance

#Usage

Step 1: Fetch Historical Data
Use yfinance to download historical data for the S&P 500 index (^GSPC), WTI crude oil (CL=F), and spot gold (GC=F).

Step 2: Data Preprocessing
Read the downloaded data into pandas DataFrames, ensuring proper datetime formatting for time series analysis.

Step 3: Visualization
Visualize the historical data using hvplot to generate interactive charts, aiding in the exploration of trends and patterns.

Step 4: Forecasting
Employ the Prophet library to forecast future market prices. Adjust the model parameters as necessary to improve forecast accuracy.

## Examples and Analysis Summary

The notebook includes several examples demonstrating each step of the analysis:

Fetching Data: Code snippets show how to use yfinance to fetch historical price data.

Visualization: Interactive plots of the S&P 500, WTI crude oil, and spot gold prices are created using hvplot, showcasing significant market trends over the last five years.

Forecasting Results: The Prophet library is used to forecast future prices, with visualizations of the forecasted trends. A summary of the forecasting results is provided, discussing potential market directions.

## Directory

Primary and final code file is "MAIN_CODE_FINAL.ipynb"

Slide presentation is "Project 1 Slides.pdf"

Documentation files:

"P1-proposal_summary.docx"

"P1_schedule.docx"


![image](https://github.com/SAG-GithubApprentice/Project-1/assets/151570128/c7b4d7a3-0e97-4365-a6c2-868df297ea60)



## Contributing

This project benefits from the contributions of:

edX Boot Camps LLC - Educational partner providing guidance and resources.

## Authors

Sergio Garzon

Chris Alvarez

Todd Snyder

## License

This project is not licensed and is available for educational and non-commercial use only.




