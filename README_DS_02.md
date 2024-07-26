# Task 2


# Introduction

The Titanic dataset is a classic dataset used in data science and machine learning for binary classification tasks. It contains information about passengers on the Titanic, including whether they survived or not. This project aims to clean the data, explore the relationships between variables, and identify patterns and trends.



# Dataset
The Titanic dataset contains information about the passengers who were aboard the Titanic, including their age, gender, class, and whether they survived the disaster. 
https://github.com/datasciencedojo/datasets/blob/master/titanic.csv




# Data Cleaning

The following steps were performed to clean the data:

1. Handling Missing Values:
   Filled missing values for `Age` with the median age.
   Filled missing values for `Embarked` with the mode.
   Dropped the `Cabin` column due to excessive missing values.
   

2. Converting Categorical Variables:
   Converted `Sex` to numerical values (0 for male, 1 for female).
   Converted `Embarked` to numerical values (0 for S, 1 for C, 2 for Q).


3. Removing Duplicates:
   Checked for and removed any duplicate rows.


  

# Exploratory Data Analysis (EDA)

The following analyses were conducted:

1. Descriptive Statistics:
    Generated summary statistics for numerical columns.
     

2. Visualizing Distributions:
   Plotted histograms for `Age` and `Fare`.
   Created a count plot for the `Survived` column.
     

3. Exploring Relationships Between Variables:
    Visualized survival rates by `Sex` and `Pclass` using bar plots.
    Created a pair plot to explore relationships between numerical variables.
     

# Conclusion

The output of the dataset, shows the steps taken for data cleaning, the exploratory data analysis performed, and how to use the provided dataset.
