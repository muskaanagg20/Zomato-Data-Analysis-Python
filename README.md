# 🍽️ Zomato Data Analysis Project 🍽️

![Python](https://img.shields.io/badge/Python-3.8-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3.3-blue.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.3-blue.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11.2-blue.svg)

## Overview

This project involves a comprehensive analysis of Zomato's restaurant data to extract insights related to customer preferences, restaurant ratings, and spending patterns. The analysis was conducted using Python within a Jupyter Notebook environment, leveraging powerful data manipulation and visualization libraries.

## Table of Contents

- [Dataset](#dataset)
- [Tools Used](#tools-used)
- [Analysis Steps](#analysis-steps)
- [Files Included](#files-included)
- [Usage](#usage)
- [Conclusion](#conclusion)

## Dataset

The dataset, `zomato_data.csv`, includes the following columns:
- **name**: Name of the restaurant
- **online_order**: Indicates whether the restaurant accepts online orders (Yes/No)
- **book_table**: Indicates whether the restaurant allows table bookings (Yes/No)
- **rate**: Ratings given by customers
- **votes**: Number of votes received by the restaurant
- **approx_cost(for two people)**: Approximate cost for two people
- **listed_in(type)**: Type of restaurant (e.g., cafe, buffet, dining, etc.)

## Tools Used

- **Python**: Core programming language for data analysis.
- **Jupyter Notebook**: Interactive environment for code execution, data visualization, and analysis.
- **Pandas**: Library for data manipulation and analysis.
- **NumPy**: Library for numerical operations and array manipulation.
- **Matplotlib & Seaborn**: Libraries for creating static, animated, and interactive visualizations.

## Analysis Steps

1. **Data Loading**: Import the CSV file into a Pandas DataFrame.
2. **Data Cleaning**: Handle missing values, remove duplicates, and prepare the data for analysis.
3. **Exploratory Data Analysis (EDA)**: Generate summary statistics, explore relationships between variables, and derive insights.
4. **Data Visualization**: Create visualizations to illustrate:
   - The types of restaurants most ordered from.
   - The distribution of votes across different types of restaurants.
   - The ratings that the majority of restaurants have received.
   - The average spending by couples who order online.
   - The mode (online or offline) with the highest ratings.
   - The type of restaurant that received more offline orders.

## Files Included

- `zomato_data.csv`: Raw dataset used for analysis.
- `zomato_data_analysis.ipynb`: Jupyter Notebook containing the Python code for the analysis.

## Usage

To reproduce the analysis:
1. Clone the repository or download the files to your local machine.
    ```sh
    git clone https://github.com/yourusername/zomato-data-analysis.git
    cd zomato-data-analysis
    ```
2. Ensure you have Python installed along with the necessary libraries: Pandas, Matplotlib, and Seaborn.
    ```sh
    pip install pandas matplotlib seaborn jupyter
    ```
3. Open `zomato_data_analysis.ipynb` in Jupyter Notebook.
    ```sh
    jupyter notebook zomato_data_analysis.ipynb
    ```
4. Run the cells in the notebook sequentially to perform the analysis step-by-step.

## Conclusion

The Zomato data analysis reveals key insights into customer preferences, restaurant ratings, and spending patterns, offering valuable information for strategic decision-making and marketing initiatives.

---

⭐️ If you found this project interesting or helpful, please give it a star! ⭐️
