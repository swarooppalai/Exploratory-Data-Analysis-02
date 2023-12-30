# Airline Data Exploratory Data Analysis(EDA)
This code performs comprehensive data analysis on an airlines dataset using SQL and Python, exploring aspects such as seat occupancy rates, revenue trends over time, and average charges for different fare conditions on each aircraft. Visualizations, including line and bar charts, are utilized to provide insights into the dataset's key features and enable strategic decision-making for optimizing aircraft occupancy and pricing.


# Airlines Data Analysis Readme

## Overview

This Python script, along with SQL queries, performs data analysis on an airlines dataset obtained from Kaggle. The analysis covers various aspects such as seat occupancy rates, revenue trends over time, and average charges for different fare conditions on each aircraft. The code utilizes libraries such as Pandas, Matplotlib, Seaborn, and SQLite3 for data manipulation, visualization, and database interaction.

## Instructions

### 1. Dataset

Make sure to download the airlines dataset from Kaggle and save it as 'travel.sqlite' in the same directory as the script.

Dataset Link: [Airlines Dataset on Kaggle](https://www.kaggle.com/datasets/saadharoon27/airlines-dataset)

### 2. Libraries

Ensure that you have the necessary libraries installed. You can install them using the following:

```bash
pip install pandas matplotlib seaborn sqlite3
```

### 3. Running the Script

Run the script in a Jupyter notebook or any Python environment. The script will connect to the database, perform SQL queries, and generate visualizations to provide insights into the airlines dataset.

## Contents

1. **Importing Libraries**: Importing necessary Python libraries for data analysis and visualization.

2. **Connecting the Database**: Establishing a connection to the SQLite database containing the airlines dataset.

3. **Data Exploration**: Exploring the tables in the dataset, checking for missing values, and running specific SQL queries for analysis.

4. **Analyzing Occupancy Rate**: Analyzing seat occupancy rates for each aircraft and visualizing the results.

5. **Revenue Analysis**: Investigating the number of tickets booked and total revenue over time, as well as calculating average charges for each aircraft with different fare conditions.

6. **Total and Average Revenue**: Analyzing total revenue and average revenue per ticket for each aircraft.

7. **Increasing Occupancy Rate**: Simulating the impact of a 10% higher occupancy rate on total annual turnover.

8. **Basic Analysis**: Basic analysis of the dataset, including the number of planes with more than 100 seats and how the number of tickets booked and total amount earned changed over time.

## Conclusion

This script provides a comprehensive analysis of the airlines dataset, offering valuable insights for optimizing seat occupancy, pricing strategies, and overall revenue management. Adjustments and enhancements can be made based on specific business goals and objectives.

Feel free to customize the script further to suit specific requirements or integrate it into a larger data analysis pipeline.
