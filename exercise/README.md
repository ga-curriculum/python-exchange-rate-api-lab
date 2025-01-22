<h1>
  <span class="headline">Python ExchangeRate API Lab</span>
  <span class="subhead">Exercise</span>
</h1>

## Overview

In this lab, you will practice making API calls using Python's `requests` library. You'll use the Exchange Rate API to fetch current currency exchange rates and manipulate the data within your Python program. This exercise will help you understand how to interact with web APIs, handle JSON data, and build a simple currency converter.

## Objectives

- Use the requests library to make HTTP GET requests to an API.
- Parse and extract data from JSON responses.
- Handle user input to create dynamic API queries.
- Implement basic error handling for API responses.

## Instructions

1. Import the `requests` package into your Python file.

2. Sign up for a free account to get your API key.

   - Visit Exchange Rate API to sign up for a free account.
   - After signing up, you'll receive an API key. Keep this key secure and avoid sharing it publicly.

3. Set up the API endpoint URL.

   The base URL for fetching the latest exchange rates is:

   ```bash
   https://v6.exchangerate-api.com/v6/YOUR-API-KEY/latest/USD
   ```

   - Replace `YOUR-API-KEY` with the API key you obtained.

   - Replace USD with the three-letter currency code you want to use as the base currency (ex: EUR, JPY, GBP).

4. Make a GET request to the API endpoint using the requests library.

5. Parse the JSON response to extract the exchange rate for a target currency.

   - The JSON response contains a key called conversion_rates, which is a dictionary of currency codes and their exchange rates relative to the base currency.
   - Refer to the [Exchange Rate API Python Documentation](https://www.exchangerate-api.com/docs/python-currency-api) for more detailed usage information.

6. Print the exchange rate.

   - Display the exchange rate using a formatted string:

   ```python
   print(f"The exchange rate from USD to EUR is {exchange_rate}")
   ```

7. Test your code by running

   ```bash
   python3 main.py
   ```

   Ensure your program outputs the correct exchange rate.
