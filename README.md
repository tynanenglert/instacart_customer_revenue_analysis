# Instacart Customer Analysis 
This is a study of Instacart’s customers that seeks to analyze purchasing behaviors.  The aim is to identify distinct customer segments and gather information about consumption patterns to better inform targeted marketing campaigns.

## Table of Contents

- Data Sources
- Getting Started
- Data Analysis
- Results

## Data Sources

This is a publicly dataset of Instacart online grocery shopping from 2017.  

## Getting Started

To begin this analysis, I imported the dataset into Jupyter Notebooks and performed the necessary cleaning and consistency checks to prepare the data for further analysis.  I merged customer, product and department tables into a unified dataset and derived new variables such as order frequency, spending amount, and customer loyalty.

## Data Analysis 

I took the cleaned and combined data and grouped customers based on age, income, family status, and specific shopping categories.  Using crosstabs, I analyzed each group across region, department, spending amount and order frequency.  I plotted each crosstab into bar charts to better visualize the results, and identify any distinctions among categories.  

## Results

My analysis didn’t identify any significant differences among these groups with regard to purchasing habits, but the categories I added provide a good jumping off point for further analysis.  A future addition to this analysis could be a cluster analysis using Kmeans, and using the categories from this analysis to better understand each cluster.  

