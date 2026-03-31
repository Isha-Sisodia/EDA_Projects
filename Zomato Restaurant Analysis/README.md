# Zomato Data Analysis & Insights

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Zomato dataset to understand restaurant trends, customer preferences, and factors affecting ratings and engagement.

The goal is to extract meaningful insights from real-world data using Python and data analysis libraries.

## Data Source

Kaggle Dataset:
https://www.kaggle.com/datasets/mathurutkarsh/zomato-dataset?select=zomato.csv

## Dataset

* Zomato Restaurant Dataset
* Contains information about restaurants including:

  * Name, City, Cuisines
  * Ratings and Votes
  * Cost for two
  * Online delivery and table booking

## Objectives

* Analyze restaurant distribution across cities
* Understand rating patterns and customer behavior
* Explore the impact of cost, votes, and services on ratings
* Identify top-performing restaurants and cuisines
* Derive business insights from data

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Data Cleaning

* Handled missing values in Cuisines column
* Removed duplicate records
* Ensured correct data types

## Feature Engineering

Created new features to enhance analysis:

* cost_per_vote – Measures value for money
* rating_per_vote – Measures rating efficiency
* cost_category – Categorized restaurants into Low, Medium, High

## Key Analysis and Insights

### City Analysis

* Major cities have the highest number of restaurants
* Indicates higher demand in urban areas

### Rating Distribution

* Most ratings fall between 3.0 and 4.5
* Extreme ratings are rare

### Cost vs Rating

* Higher cost restaurants tend to have slightly better ratings
* Price influences quality perception but is not the only factor

### Votes vs Rating

* Weak positive relationship between votes and ratings
* Popularity does not always guarantee quality

### Online Delivery Impact

* Restaurants offering online delivery show similar or slightly better ratings
* Convenience plays a role in customer satisfaction

### Cuisine Analysis

* A few cuisines dominate the dataset
* Customer preferences are concentrated around popular food types

### Advanced Insights

* Identified value-for-money restaurants using cost_per_vote
* Found high-quality low-popularity restaurants using rating_per_vote

## Visualizations

* Bar charts (City distribution, Cuisines)
* Scatter plots (Cost vs Rating, Votes vs Rating)
* Histogram (Rating distribution)
* Heatmap (Correlation analysis)

## Conclusion

* Restaurant distribution is concentrated in major cities
* Ratings are generally moderate
* Cost has a slight impact on ratings
* Customer engagement depends on multiple factors such as service, cost, and convenience
* Data-driven insights can help businesses improve decision-making
