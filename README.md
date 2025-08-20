# Zomato-Data-Analysis

Overview
This project is a Jupyter Notebook-based analysis of the Zomato dataset, which contains information about various restaurants listed on the Zomato platform. The dataset includes details such as restaurant names, locations, cuisines, ratings, and more. The goal of this project is to explore and analyze the data to derive insights about restaurant trends, customer preferences, and other factors influencing the food industry.

Dataset
The dataset used in this project is zomato.csv, which contains 9551 entries and 21 columns. Some of the key columns include:

Restaurant ID

Restaurant Name

Country Code

City

Address

Cuisines

Average Cost for two

Currency

Has Table booking

Has Online delivery

Aggregate rating

Rating color

Rating text

Votes

Project Structure
The project is organized as follows:

Data Loading: The dataset is loaded into a pandas DataFrame for analysis.

Data Exploration: Initial exploration includes viewing the first and last few rows, checking data types, and identifying missing values.

Data Cleaning: Handling missing values and removing unnecessary columns.

Visualization: Using seaborn and matplotlib to create visualizations that highlight trends and patterns in the data.

Key Steps
Import Libraries: Essential libraries such as pandas, numpy, seaborn, and matplotlib are imported.

Load Data: The dataset is loaded from zomato.csv.

Initial Inspection: The first and last few rows are displayed to get a sense of the data.

Data Info: Basic information about the dataset, including data types and non-null counts.

Missing Values: Identification and handling of missing values in the dataset.

Data Cleaning: Removal of the Switch to order menu column and checking for duplicates.

Visualization: A countplot is created to show the distribution of restaurants by country code.

Requirements
To run this project, you need the following Python libraries:

pandas

numpy

seaborn

matplotlib
