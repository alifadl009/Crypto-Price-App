# Crypto Price App

![Crypto Price App Logo](logo.jpg)

This Streamlit app retrieves cryptocurrency prices for the top 100 cryptocurrencies from CoinMarketCap and provides various visualization options to analyze the data.

## About

This app is built using Python and relies on several external libraries for data manipulation, visualization, web scraping, and more. Below are some key details about the app:

- **Python libraries:** The app utilizes various Python libraries, including Streamlit, PIL (Pillow), pandas, base64, matplotlib, BeautifulSoup, requests, and json.

- **Data source:** The cryptocurrency price data is obtained from [CoinMarketCap](http://coinmarketcap.com) using web scraping techniques.

- **Credit:** The web scraper used in the app is adapted from the Medium article *[Web Scraping Crypto Prices With Python](https://towardsdatascience.com/web-scraping-crypto-prices-with-python-41072ea5b5bf)*, written by [Bryan Feng](https://medium.com/@bryanf).

## Usage

1. The user can select the currency in which they want to view the cryptocurrency prices (USD, BTC, or ETH) from the input options on the left sidebar.

2. The app displays a table with the top 100 cryptocurrencies' price data based on the selected currency.

3. The user can select specific cryptocurrencies from the sidebar to display their price data.

4. The user can use the slider to choose the number of top cryptocurrencies they want to display in the table.

5. The user can select the time frame (7 days, 24 hours, or 1 hour) for percentage price change analysis.

6. The user can choose whether to sort the data based on percentage price change.

7. The app presents a table of the selected cryptocurrencies' percentage price changes over the chosen time frame.

8. A downloadable link to a CSV file containing the data of the selected cryptocurrencies is provided below the table.

9. The app also visualizes the percentage price changes in the form of bar plots for the selected time frame.

## How to Run the App

To run this Streamlit app, make sure you have the required Python libraries installed. You can install them using `pip`:

```bash
pip install streamlit pandas matplotlib seaborn BeautifulSoup4 requests
```
1. Save the provided code into a Python file (e.g., crypto_price_app.py).

2. Ensure you have the logo.jpg file in the same directory as the Python file. This image will be used as the logo for the app.

3. Open a terminal or command prompt and navigate to the directory containing the Python file.

Run the Streamlit app using the following command:
```bash
streamlit run crypto_price_app.py
```
The app will launch in your default web browser, and you can interact with it using the provided input options.
Enjoy exploring cryptocurrency prices with this Crypto Price App!
