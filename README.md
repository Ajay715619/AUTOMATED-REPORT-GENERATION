# Sales Report Generator

## Overview
This Python script reads sales data from a CSV file, performs basic analysis, and generates a PDF report using the `fpdf` library.

## Features
- Reads sales data from `data.csv`.
- Computes total and average sales and profit.
- Generates a formatted PDF report including summary statistics and a table of data.

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install pandas fpdf
```

## Usage
1. Ensure `data.csv` exists in the same directory as the script.
2. The CSV file should have the following columns: `Date`, `Sales`, and `Profit`.
3. Run the script using Python:

```bash
python sales_report.py
```

## Expected Output
- The script calculates:
  - Total Sales
  - Total Profit
  - Average Sales
  - Average Profit
- A PDF report named `sales_report.pdf` is generated in the current directory.

## Configuration
- Modify `csv_file` variable to change the input data source.
- Adjust PDF formatting or add additional fields as needed.

## License
This project is licensed under the MIT License.

