Currency Converter
This Currency Converter project provides two methods to convert amounts between different currencies using exchange rates. You can either:
Load exchange rates from a JSON file (offline).
Fetch live exchange rates from an API (online).

Features
Convert Currency Amounts: Converts amounts between specified base and target currencies.
Offline Mode: Uses exchange rates from a rates.json file for offline conversion.
Online Mode: Fetches up-to-date exchange rates from the Frankfurter API for online conversion.
Error Handling: Displays informative errors for invalid currency codes or missing exchange rates.

How It Works
Offline Mode (JSON file)
The script loads exchange rates from a local rates.json file, which should have the following structure:
{
    "rates": {
        "USD": 1.12,
        "GBP": 0.85,
        "INR": 88.56,
        ...
    }
}
To convert using offline mode:

Update the rates.json file with the latest rates.
Run the script, which loads rates from the JSON file and performs the conversion.
Online Mode (API)
The script fetches live exchange rates from the Frankfurter API with a specified base currency. This ensures the latest conversion rates are used every time.

To convert using online mode:
Set the desired base currency in load_rates(base_currency='EUR').
The script retrieves live rates from the API and converts the amount to the target currency.

Usage
Offline Mode:
# Make sure you have a rates.json file in the same directory
rates = load_rates('rates.json')
result = convert(amount=10, base='USD', to='EUR', rates=rates)
print(result)

Online Mode:
result = convert(amount=10, base='USD', to='INR')
print(result)

Example Output
Offline Mode:
10 USD to EUR: 8.93

Online Mode:
10 USD to INR: 752.85

Requirements
Python 3.x
For online mode, the requests library is required:
pip install requests

Error Handling
If an invalid currency code is provided, an error message lists the available currencies.
For missing currency rates in the JSON file or API response, the converter raises an informative exception.
