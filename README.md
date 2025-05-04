## Sales Data Summary and Visualization
## Overview
This project demonstrates how to build, populate, and analyze a simple sales database using SQLite and Python. It automates the process of creating a database, generating dummy sales data, performing SQL-based analysis, and visualizing sales performance.

## The script:

Creates a SQLite database with a sales table.

Inserts 8,000 rows of randomly generated sales data.

Calculates total quantity sold and total revenue for each product.

## Displays a summary report.

Generates and saves a revenue bar chart as an image.

This is an excellent starter project for beginners learning database operations, SQL querying, and Python-based data visualization.

## Features
Database creation and management with SQLite.

Automated dummy data generation using NumPy.

Data summarization using SQL queries executed via Pandas.

Visualization of revenue per product with Matplotlib.

Structured and modular code with error handling and logging.

## Requirements
Python version 3.6 or higher

Required Python libraries:

pandas

matplotlib

numpy

Dependencies can be installed using pip.

## Usage
To use this project:

Clone the repository from GitHub.

Navigate to the project directory.

Run the main script using Python.

## Upon execution, the script will:

Create the SQLite database if it doesn't exist.

Populate the database with dummy sales data (if empty).

Output a product-wise sales summary.

Display and save a bar chart of revenue by product.

## Project Structure
sales_summary.py: Main Python script that handles database operations and chart creation.

sales_data.db: SQLite database file (auto-generated after running the script).

sales_chart.png: Revenue visualization saved as a PNG image.

README.md: Project documentation and instructions.

