# Forest Fires Data Analysis - Assignment

This repository contains the code and analysis for the Forest Fires dataset from the UCI Machine Learning Repository. The dataset consists of meteorological and fire data recorded in Portugal. This assignment was completed as part of the Data Analytics, Big Data, and Predictive Analytics Certificate.

---

## Assignment Overview

In this assignment, I performed various data manipulation, exploration, and visualization tasks using Python and libraries such as Pandas, NumPy, Matplotlib, and Seaborn to analyze the Forest Fires dataset. The main objectives of the tasks are to clean, filter, aggregate, and visualize the dataset to uncover insights about the forest fires.

---

## Tasks

The following tasks were completed in this assignment, with code answering each of the questions provided:

1. Read and inspect the dataset: Import the dataset from a URL and display the first five records to understand its structure.
2. Data Exploration: Count the total number of observations and filter those with both significant fire (burned area > 0) and rain.
3. Filtering Data: Show the columns month, day, and area for all observations where the burned area is greater than 0.
4. Sorting and Ranking: Identify the five largest fires (i.e., the records with the largest burned area).
5. Data Selection: Extract corresponding month, temperature, RH, wind, rain, and area for the largest fires.
6. Reordering Factor Levels: Reorder the month column to ensure months are ordered from January to December.
7. Feature Engineering: Add a new column fire_occurred to indicate whether a fire occurred (area > 0).
8. Aggregation: Calculate the mean values of area, wind, temp, and RH for each month.
9. Exploratory Data Analysis (EDA): Count the number of observations per month and visualize the results with a bar plot.
10. Visualization: Count and visualize the number of observations with a burned area greater than zero per month using a bar plot.

---

## Files

- forestfires_analysis.ipynb: The notebook file containg the solutions for the tasks. It includes all the code to load, process, and analyze the data.
- forestfires.csv: The dataset used for analysis

---

## Tools Used
1. Python
2. Pandas
3. NumPy
4. Matplotlib/Seaborn
5. Jupyter Notebook

