# IMDB Movie Genre Budget Analysis
This file contains code that analyzes the budget distribution across different movie genres using data from the IMDB database. The goal is to calculate the budget distribution as a percentage for each genre and visualize it using a pie chart.

## Introduction
This script connects to the IMDB SQLite database and retrieves budget data for movies across different genres. The budget distribution is then calculated and visualized using a pie chart. This analysis provides insights into how budgets are distributed among different movie genres.

## Data
The analysis uses data from the IMDB database. The IMDB.sqlite database file is expected to have a table named IMDB with columns like Movie_id, budget, and other relevant information. Ensure that the database schema matches the code's expectations.

## Analysis
The script performs the following steps:

1.Connects to the SQLite database.
2.Replaces empty budget entries with zero to ensure accurate calculations.
3.Queries the database to calculate the total budget for each genre (excluding rows with no genre).
4.Calculates the budget percentage for each genre.
5.Sorts the genre percentages by percentage in descending order.
6.Prints the genre and its budget percentage.
7.Generates a pie chart using Matplotlib to visualize the budget distribution.

## Results
The script will output the budget percentages for each movie genre and display a pie chart visualization in the terminal. The pie chart provides an intuitive representation of how budgets are allocated among different genres.
