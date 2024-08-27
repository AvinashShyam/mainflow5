# USD Currency Converter Application

## Overview

This is a Python-based USD Currency Converter application that provides a simple graphical user interface (GUI) for converting USD to various other currencies. The application fetches real-time exchange rates and ensures accurate conversions. It's designed for ease of use, making currency conversion quick and straightforward.

## Features

- **Real-time Currency Conversion:** Converts USD to multiple currencies using up-to-date exchange rates.
- **User-Friendly GUI:** Simple and intuitive interface designed using Tkinter.
- **Responsive Design:** Input fields for USD, dropdown menus for target currencies, and buttons for conversion and refreshing exchange rates.

## Technologies Used

- **Python:** The core programming language used for development.
- **Tkinter:** Python’s standard GUI library, used for designing the application interface.
- **Requests:** Used for making API calls to fetch the latest currency exchange rates.

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/AvinashShyam/usd-currency-converter.git
   cd usd-currency-converter
   ```

2. **Install Required Libraries:**
   Make sure you have Python installed. Then, install the required Python libraries:
   ```bash
   pip install requests
   ```

3. **Run the Application:**
   Start the application by running:
   ```bash
   python currency_converter.py
   ```

## Usage

1. Open the application.
2. Enter the amount in USD that you want to convert.
3. Select the target currency from the dropdown menu.
4. Click the "Convert" button to see the converted amount.
5. Use the "Refresh Rates" button to update the exchange rates.

## Future Enhancements

- Add support for additional currencies.
- Implement error handling for network issues.
- Introduce a feature to track conversion history.
