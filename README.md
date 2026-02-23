# Currency_Converter
This Python program is a command-line currency converter that uses an online API to get real-time exchange rates. It sends a request to the ExchangeRate-API to fetch the latest rates for a selected source currency. The program checks for errors such as invalid currency codes, network issues, or negative amounts.
💱 Currency Converter (Python)

A simple command-line currency converter built in Python that fetches real-time exchange rates from an online API and converts amounts between different currencies.

🚀 Features

🌍 Real-time exchange rates using ExchangeRate-API

💲 Convert between any supported currency codes (USD, EUR, INR, GBP, etc.)

⚠️ Error handling for:

Invalid currency codes

Network/API issues

Negative or invalid input amounts

🖥️ Simple and user-friendly command-line interface

🛠️ Technologies Used

Python 3

requests library

ExchangeRate-API

📦 Installation

Clone this repository:

git clone https://github.com/rakshithadr/currency-converter.git

Navigate to the project folder:

cd currency-converter

Install required dependency:

pip install requests
▶️ Usage

Run the script:

python currency_converter.py

Then enter:

Source currency code (e.g., USD)

Target currency code (e.g., EUR)

Amount to convert

Example:

100 USD = 92.50 EUR
Exchange Rate: 1 USD = 0.9250 EUR
📁 Project Structure
currency-converter/
│
├── currency_converter.py
└── README.md
