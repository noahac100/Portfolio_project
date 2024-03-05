# Financial Manager README

The Financial Manager is a Python-based money management tool designed to provide users with insights into their financial transactions, categorize expenses, and facilitate informed decision-making. This README provides essential information to set up and utilize the Financial Manager effectively.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Financial Manager connects to a Google Drive spreadsheet containing financial transaction data and uses the Pandas library for data manipulation. It categorizes transactions, visualizes monthly expenses, calculates savings, and offers an interactive interface for users to explore their financial data.

## Features

1. **Data Connection:**
   - Connects to a Google Drive spreadsheet using `gspread` for seamless data access.

2. **Data Cleaning and Categorization:**
   - Cleans and organizes transaction data, categorizing expenses based on keywords.

3. **Monthly Expense Analysis:**
   - Visualizes and categorizes monthly expenses with an interactive bar chart.

4. **Income and Savings Calculation:**
   - Allows users to input income, recurring, and non-recurring expenses for monthly savings calculation.

5. **Detailed Monthly Expense Breakdown:**
   - Provides a granular breakdown of monthly expenses by category over time.

6. **Interactive Summary Table:**
   - Dynamically updates based on the selected expense category for detailed examination.

7. **Motivational Interface:**
   - Incorporates motivational quotes and imagery to inspire users on their financial journey.

8. **Flexible Deployment:**
   - Hosted within a Panel (pn) environment for an interactive and customizable experience.

## Prerequisites

Before using the Financial Manager, ensure you have the following installed:

- Python (3.6 or higher)
- `gspread` library
- `pandas` library
- `panel` library

Install the required libraries using:
```bash
pip install gspread pandas panel
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/noahac100/financial-manager.git
   ```

2. Navigate to the project directory:
   ```bash
   cd financial-manager
   ```

3. Run the Financial Manager script:
   ```bash
   python financial_manager.py
   ```

## Usage

1. Connect to your Google Drive spreadsheet by providing the necessary credentials.
2. Explore the interactive interface to visualize and analyze your financial data.
3. Input income, recurring, and non-recurring expenses to calculate monthly savings.
4. Customize and filter data to gain insights into specific expense categories.

## Customization

- **Expense Categories:**
  Customize expense categories by modifying the categorization rules in the script.

- **Motivational Content:**
  Personalize motivational quotes and imagery by updating the relevant sections in the code.

## Contributing

Contributions are welcome! If you'd like to enhance or add features, please follow the [contribution guidelines](CONTRIBUTING.md).
