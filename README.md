# Zomato Data Analysis Using Python

## Project Overview

This project performs exploratory data analysis on Zomato restaurant
data using Python.

The analysis focuses on understanding restaurant ratings, customer
engagement, online ordering, table booking, restaurant types, and
approximate cost for two people.

The project uses Python libraries such as Pandas, NumPy, Matplotlib,
and Seaborn for data cleaning, analysis, and visualization.

## Objectives

- Understand the structure and characteristics of the Zomato dataset
- Clean and prepare restaurant rating data
- Analyze restaurant types
- Analyze online ordering availability
- Analyze table booking availability
- Study restaurant ratings
- Analyze customer votes and engagement
- Analyze approximate cost for two people
- Identify relationships between ratings, votes, and cost
- Generate business-oriented insights from the data

## Dataset

The dataset contains information about 148 restaurants and includes
the following variables:

- Restaurant Name
- Online Order
- Table Booking
- Rating
- Votes
- Approximate Cost for Two People
- Restaurant Type

## Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas
2. Inspected the first and last records
3. Checked the dataset dimensions
4. Checked data types
5. Checked for missing values
6. Converted restaurant ratings from formats such as "4.1/5"
   into numeric values such as 4.1
7. Performed descriptive statistical analysis

## Data Quality

The dataset contains 148 records and 7 columns after preprocessing.

No missing values were found in the dataset.

## Exploratory Data Analysis

The project analyzes:

### Restaurant Types

The dataset contains four major restaurant categories:

- Dining
- Cafes
- Buffet
- Other

Dining is the dominant restaurant type in the dataset.

### Online Ordering

The project compares restaurants that provide online ordering
with those that do not.

### Table Booking

The analysis examines table booking availability across different
restaurant types.

### Ratings

Restaurant ratings are analyzed using descriptive statistics and
visualizations.

### Votes

Customer votes are analyzed to understand restaurant popularity
and customer engagement.

### Cost Analysis

The approximate cost for two people is analyzed to understand
restaurant pricing patterns.

### Correlation Analysis

Correlation between numerical variables such as rating, votes,
and approximate cost is examined using a correlation heatmap.

## Key Findings

- Dining is the most common restaurant category in the dataset.
- The average restaurant rating is approximately 3.63 out of 5.
- The average number of votes per restaurant is approximately 265.
- Votes show substantial variation across restaurants.
- The average approximate cost for two people is approximately ₹418.
- Most restaurants in the dataset fall within a moderate price range.
- Online ordering is more common among cafes and smaller outlets,
  while dining restaurants rely more heavily on traditional
  in-person service.
- Restaurants with higher numbers of votes generally tend to have
  higher ratings.
- Price has a relatively weak relationship with restaurant rating.

## Visualizations

The project includes visualizations such as:

- Restaurant type distribution
- Online order analysis
- Table booking analysis
- Cost distribution
- Rating distribution
- Average rating by restaurant type
- Votes by restaurant type
- Correlation heatmap
- Online order and restaurant type heatmap

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab

## Project Workflow

Data Loading
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Data Preprocessing
     ↓
Descriptive Statistics
     ↓
Exploratory Data Analysis
     ↓
Data Visualization
     ↓
Correlation Analysis
     ↓
Business Insights
     ↓
Conclusion
