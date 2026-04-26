# Dataset_cleaning-sorting

Data Analysis Project
Overview

This project involves data cleaning, analysis, and visualization using Python's Pandas, NumPy, and Seaborn libraries. The primary goal is to transform a raw dataset into a cleaned version and provide insights through visual representations.
Raw Data

The raw data is stored in raw_data.csv, consisting of 100 entries with the following columns:

    ID: Unique identifier for each entry.
    Name: Name of the individual.
    Age: Age of the individual (with some missing values).
    Score: Performance score (with some missing and NA values).
    Category: Category assigned to the entries (A or B).

Sample Data
plaintext

ID,Name,Age,Score,Category
1,John,23,85,A
2,Jane,29,78,B
...
100,Luke,22,85,B

Data Cleaning

The data cleaning process included the following steps:

    Handled Missing Values:
        Filled missing Age values with the median age.
        Replaced NA in the Score column with NaN and filled remaining missing scores with the mean score.
        Dropped rows with missing Name or Category.

    Sorting:
        The dataset was sorted based on the Score column in descending order.

Visualization

The project includes a bar plot visualizing scores by individual names, using Seaborn for a clear and visually appealing representation.
Cleaned Data

The cleaned data is saved in cleaned_data.csv, which can be used for further analysis or reporting.
Requirements

To run this project, make sure you have the following Python packages installed:

    pandas
    numpy
    matplotlib
    seaborn

You can install the required packages using pip:
bash

pip install pandas numpy matplotlib seaborn

Usage

    Place the raw_data.csv file in the same directory as the Python script.
    Run the Python script to clean the data, create the visualizations, and save the cleaned data.

bash

python data_analysis.py

Conclusion

This project demonstrates essential data analysis skills, including data cleaning, transformation, and visualization. The outcome provides insights into individual scores, highlighting patterns and anomalies in the dataset.

Feel free to modify and expand upon this project for your data analysis needs!
