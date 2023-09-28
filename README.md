# Stock Market Data Visualization Web Application

This is a simple web application built with [Streamlit](https://streamlit.io/) that allows you to visualize stock market data for Google (GOOGL) and Microsoft (MSFT). It leverages the [Yahoo Finance](https://finance.yahoo.com/) API to fetch and display historical stock data and company information.

## Features

- **Interactive Data Visualization:** The application provides interactive line charts that display the historical stock prices for Google and Microsoft.
- **Company Information:** You can also access detailed information about each company, including a long business summary.

## Installation

To run this application locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/AnuragNagare/stock-market-app.git


Install the required Python libraries using pip:
pip install streamlit yfinance

Run the Streamlit application:
streamlit run app.py

Open your web browser and go to the URL provided by Streamlit (usually http://localhost:8501) to interact with the application.

Features:
Displays stock market data for Google and Microsoft.
Allows users to select a date range to view historical data.
Presents detailed company information.
Visualizes historical data with line charts.

Usage
Choose the company (Google or Microsoft) from the sidebar.
Select a date range by using the date picker in the Streamlit interface.
View detailed company information and historical stock data.
Explore line charts to analyze stock performance.

Dependencies
Streamlit
yfinance
