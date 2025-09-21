# Automated ETL Pipeline for Sales Data 🚀

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An automated ETL (Extract, Transform, Load) pipeline built with Python to process raw sales data from CSV files and load it into a structured, queryable SQLite database. This project demonstrates a complete data engineering workflow for cleaning, enriching, and storing data for analysis.

***

## ✨ Features

- **Extract:** Reads data efficiently from CSV files.
- **Transform:**
    - Cleans and standardizes column names.
    - Converts data types for consistency (e.g., strings to datetime objects).
    - Handles missing or null values.
    - **Feature Engineering:** Creates a new `profit_margin` column for deeper analysis.
- **Load:** Loads the clean, transformed data into an SQLite database table, replacing old data to ensure idempotency.

***

## 🛠️ Technologies Used

- **Python**: The core programming language for the script.
- **Pandas**: For data manipulation, transformation, and analysis.
- **SQLite**: As the relational database for storing the structured data.

***

## ⚙️ Setup and Installation

To run this script locally, follow these steps:

**1. Clone the repository:**
```bash
git clone [https://github.com/your-username/sales-etl-pipeline.git](https://github.com/your-username/sales-etl-pipeline.git)
cd sales-etl-pipeline
