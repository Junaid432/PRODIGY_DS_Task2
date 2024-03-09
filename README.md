# PRODIGY_DS_Task2

Titanic Dataset Analysis
This repository contains Python code for performing data analysis on the Titanic dataset. The dataset provides information about passengers aboard the Titanic, including demographic data and survival outcomes.

Dataset Overview
The Titanic dataset includes the following columns:

Survived: Whether the passenger survived (0 = No, 1 = Yes)
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Sex: Gender of the passenger
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard the Titanic
Parch: Number of parents/children aboard the Titanic
Ticket: Ticket number
Fare: Passenger fare
Cabin: Cabin number
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
Analysis Steps
Load the dataset: The dataset is loaded into a Pandas DataFrame.
Understanding the structure: The structure of the dataset is examined by displaying the first few rows and information about the dataset.
Handling missing values: Missing values in the 'Age' column are filled with the median age, and the 'Cabin' column is dropped due to too many missing values.
Exploring distributions: Distributions of numerical variables such as age and gender are visualized using histograms and count plots.
Exploring relationships: Relationships between variables such as passenger class and age, and survival rate by gender are explored using box plots and bar plots.
Identifying patterns and trends: Patterns and trends in the data, such as survival rate by age group, are identified and visualized.
Usage
To run the analysis:

Ensure you have Python installed on your system.
Install the required libraries using pip install pandas seaborn matplotlib.
Clone or download this repository to your local machine.
Replace "path_to_dataset.csv" in the Python script with the actual path to your dataset file.
Run the Python script using a Python interpreter.
