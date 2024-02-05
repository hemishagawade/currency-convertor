Currency Converter
Overview
This Currency Converter is a simple web application designed to help users convert currency values between different countries. The application utilizes the ExchangeRate-API to fetch the latest exchange rates and perform the conversion based on user input.

Features
--User-Friendly Interface: The interface is designed with a clean and user-friendly layout, making it easy for users to input conversion details.
--Currency Selection: Users can select the source and target currencies from dropdown lists, providing flexibility for a wide range of currency conversions.
-- Real-Time Conversion: The application fetches real-time exchange rates from the ExchangeRate-API, ensuring accurate and up-to-date currency conversions.

Usage
1. Open the HTML file in a web browser.
2. Select the source currency from the "From" dropdown list.
3. Select the target currency from the "To" dropdown list.
4. Enter the amount you want to convert in the "Amount" input field.
5. Click the "CONVERT" button.
6. The converted amount will be displayed below in the designated area.

Styling
The application has a visually appealing design with a background gradient and a well-defined style for buttons and containers. The styling is implemented using inline CSS within the HTML file.

Dependencies
ExchangeRate-API: The application relies on the ExchangeRate-API for fetching the latest exchange rates. Make sure that the API is accessible from the network where the application is running.

Implementation Details
The conversion logic is implemented in the embedded JavaScript script within the HTML file.
The convert function is triggered when the user clicks the "CONVERT" button. It retrieves the selected currencies, fetches the exchange rates, and calculates the converted amount.

Important Note
Internet connectivity is required for the application to fetch real-time exchange rates from the ExchangeRate-API.
Ensure that the ExchangeRate-API is accessible, and there are no network restrictions preventing the API calls.

