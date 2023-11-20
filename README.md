# Supermarket_Sales_Prediction

## Overview

The aim of this project is to predict **Gender** in a supermarket sales based on a dataset containing various features related to customer transactions. By leveraging machine learning models, we intend to gain insights into sales patterns, customer behavior, and factors influencing sales in the supermarket.

## Dataset Overview

The dataset used for this project consists of the following features:

- **Invoice ID**: Unique identifier for each transaction.
- **Branch**: Branch of the supermarket.
- **City**: City where the transaction took place.
- **Customer type**: Type of customer (e.g., Member, Normal).
- **Gender**: Gender of the customer.
- **Product line**: Category of the product.
- **Unit price**: Price per unit of the product.
- **Quantity**: Quantity of the product purchased.
- **Tax 5%**: Tax amount for the product.
- **Total**: Total amount for the transaction.
- **Date**: Date of the transaction.
- **Time**: Time of the transaction.
- **Payment**: Payment method used by the customer.
- **COGS (Cost of Goods Sold)**: Cost of goods sold.
- **Gross margin percentage**: Gross margin percentage for the transaction.
- **Gross income**: Gross income for the transaction.
- **Rating**: Customer satisfaction rating.



**DATA VISUALIZATION**

## Plot 1
Represents **histograms** for each numerical column in the DataFrame df and displays them in a single figure with a specified size of 14 inches by 14 inches. 
Each histogram provides a visual representation of the distribution of values in its respective column, helping you understand the data distribution and identify patterns.

## Plot 2
Generating of a **line plot** to visualize the relationship between the **'Rating' and 'Unit price'** columns in the DataFrame.
The line plot is useful for understanding trends or patterns in how the 'Unit price' variable changes with different 'Rating' values. 
The **sns.lineplot** function automatically handles the creation of the plot with sensible default settings, making it easy to explore relationships in your data.

## Plot 3
Generation of a scatter plot to visualize the relationship between the 'Rating' and 'cogs' (cost of goods sold) columns in the DataFrame. 
Each point on the plot represents an observation in the dataset, with its x-coordinate corresponding to the 'Rating' and its y-coordinate corresponding to the 'cogs'. 
Scatter plots are useful for understanding the distribution of data points and identifying potential patterns or relationships between two variables.

## Plot 4
Generation of a scatter plot to visualize the relationship between the 'Rating' and 'cogs' (cost of goods sold) columns in the DataFrame. 
Each point on the plot represents an observation in the dataset, with its x-coordinate corresponding to the 'Rating' and its y-coordinate corresponding to the 'cogs'. 
Scatter plots are useful for understanding the distribution of data points and identifying potential patterns or relationships between two variables.



## Visualizing the relationship between different values of the n_neighbors  and KNN accuracy
Generation of a bar plot to visualize how the accuracy scores (Knn_score) vary with different values of n_neighbors. 
Each bar represents the accuracy score for a specific number of neighbors. 
The x-axis shows the different levels of n_neighbors, and the y-axis shows the corresponding accuracy scores. 


## Visualizing the relationship between Different models
Generation of a bar plot to visualize how the accuracy scores  vary with different Models. 
Each bar represents the accuracy score for a specific Model. 
The x-axis shows the different levels of MOdels, and the y-axis shows the corresponding accuracy scores. 
