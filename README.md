
# Hotstar Subscription Analysis

This project provides an exploratory data analysis (EDA) of Hotstar subscription data. The analysis covers subscription trends, demographic insights, geographic distribution, revenue forecasting, and churn prediction. The goal is to uncover patterns and trends in the data to support business strategies and decision-making.

## Dataset
The dataset includes subscription details for Hotstar users and contains the following columns:

Serial Number

User ID

Subscription Type

Monthly Revenue

Last Payment Date

Join Date

Country

Gender

Age

Device

Plan Duration

Other relevant attributes

## Key Findings

Subscription Trends:

Basic is the most popular and profitable subscription type.

Demographics:

Males predominantly prefer Basic.

Geographic Insights:

India leads in subscriber count, contributing significantly to revenue.

Revenue Forecast:

A steady increase in monthly revenue is projected over the next six months.

Churn Prediction:

A Random Forest model effectively identifies potential churners.


## Project Structure


├── data

    └── subscriptiondatadisney.xlsx  # Original dataset
├── notebooks

 
    └── hotstarsubscription.ipynb    # Jupyter notebook with EDA and analysis

    ├──requirements.txt  
└──
  
    README.md                         # Project documentation


# Analysis Steps
## Data Loading and Cleaning:

Load the dataset and check for missing values, duplicates, and data types.

## Descriptive Statistics:

Compute basic statistics and inspect distributions.
## Date Range Analysis:

Analyze the range of subscription dates.

## Subscription Analysis:

Identify the most popular subscription types and their revenue contributions.

## Demographic Analysis:

Explore subscription preferences by gender.

## Geographic Analysis:

Analyze subscriber distribution by country.

## Revenue Forecasting:

Use Exponential Smoothing to forecast monthly revenue.

## Churn Prediction:

Build a Random Forest model to predict customer churn.


# How to Use
Clone the Repository:

git clone https://github.com/Rohitmnnit/Disney-hotstarSubscriptionAnalysis
    

### Install Dependencies:
Ensure you have Python installed. Then, install the required libraries:

    pip install -r requirements.txt

### Explore the Notebook:
Open the Jupyter notebook to explore the analysis and visualize the data:

https://github.com/Rohitmnnit/Disney-hotstarSubscriptionAnalysis/blob/main/hotstarsubscription%20(1).ipynb


### Dependencies

The requirements.txt file lists all necessary dependencies for the project:


    pandas
    numpy
    matplotlib
    seaborn
    scikit-learn
    statsmodels
    jupyter

To install these dependencies, run:


    pip install -r requirements.txt

# Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.


# Contact
For any questions or feedback, please contact rohitmnnit18@gmail.com.

