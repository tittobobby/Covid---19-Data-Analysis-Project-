# Covid---19-Data-Analysis-Project-



This repository seeks to document various data analysis and cleaning tasks on a COVID-19 data set using the pandas and seaborn libraries.
Dataset is taken from : "https://raw.githubusercontent.com/SR1608/Datasets/main/covid-data.csv"

It begins by importing the necessary libraries and reading in a CSV file from a Github repository.
It then performs high-level data understanding by printing the number of rows and columns, the data types of each column, and summary statistics of the data.
It also performs low-level data understanding by finding the count of unique values in the location column, the continent with the maximum frequency, the maximum and mean values in total_cases, and the 25%, 50%, and 75% quartile values in total_deaths.
It also finds which continent has the maximum human development index and which continent has the minimum GDP per capita.
It filters the dataframe to only include certain columns
It then performs data cleaning by removing duplicates and filling in missing values with zeros
It converts the date column to a datetime format and creates a new column with the month extracted from the date
It uses groupby function to find the max value of all columns by continent and stores the result in a new dataframe named 'df_groupby'
The script continues with additional feature engineering tasks.
