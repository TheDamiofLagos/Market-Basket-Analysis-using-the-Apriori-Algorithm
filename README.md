# Market Basket Analysis with Apriori Algorithm

## Overview
This repository contains a Python script for performing Market Basket Analysis using the Apriori algorithm. The analysis is applied to a grocery sales dataset to discover associations between different products.

## Code Structure
- **Data Loading and Cleaning:** 
  - Load the grocery sales data and perform initial data cleaning.
  - Convert 'Member_number' to a string and 'Date' to datetime format.

- **Unique Transactions:**
  - Create a 'uniqueTransaction' column to group items purchased per customer per day.

- **Cross-Tabulation (Basket Creation):**
  - Create a cross-tabulation ('basket') to represent the frequency of items in each unique transaction.
  - Create a binary-encoded DataFrame ('apriori_df').

- **Apriori Algorithm and Association Rules:**
  - Apply the Apriori algorithm to generate frequent itemsets.
  - Use association rules, focusing on Zhang's metric for evaluation.

- **Heatmap Visualization:**
  - Visualize product associations using a heatmap.
  - Interpret the heatmap to understand frequent itemsets.

- **Positive Association Visualization:**
  - Explore pairs with positive Zhang's metric to highlight positive associations.

## Visualization
- Utilize heatmaps for clear and intuitive visualization of product associations.
- Explore positive associations to understand which products complement each other.

## Insights
- Use Zhang's metric for a comprehensive evaluation of association rules.
- Interpret negative and positive values to understand anti-associations and strong positive relationships.

## Future Work
- Experiment with interactive visualizations to enhance user exploration.
- Tune parameters for the Apriori algorithm to observe the impact on results.
- Conduct further data exploration for deeper insights into customer behavior.

Feel free to explore the code and adapt it for your own datasets and analysis needs.
