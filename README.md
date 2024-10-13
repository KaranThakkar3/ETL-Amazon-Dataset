# Amazon ETL Pipeline

This repository demonstrates an Extract, Transform, and Load (ETL) pipeline using Python. The project processes an Amazon product dataset, performing data cleaning, transformation, and loading the results into an SQLite database for further analysis.

## Project Overview
This project showcases the implementation of an ETL pipeline with the following steps:
1. **Extract**: Load raw Amazon product data from a CSV file.
2. **Transform**: Clean and process the data by removing unwanted characters from prices, converting ratings to numeric values, and handling missing data.
3. **Load**: Load the cleaned dataset into an SQLite database for further analysis.

## Technologies Used
- **Python 3.x**
- **Pandas**: For data manipulation and transformation.
- **SQLite**: For simulating a database environment and storing the transformed data.
- **SQLAlchemy**: For database interactions with SQLite.

## Dataset
The dataset contains information on Amazon products, including:
- Product details: `product_id`, `product_name`, `category`, `discounted_price`, `actual_price`
- Reviews: `rating`, `rating_count`
- Additional metadata: `about_product`, `user_id`, `user_name`, etc.

The raw dataset is stored in a CSV format.
