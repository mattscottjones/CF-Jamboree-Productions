# Jamboree Productions - Open Exploratory Analysis

## CONTEXT
Instacart, an online grocery store that operates through an app, already has great sales, but they want to uncover more information about their sales patterns. Instacart stakeholders are most interested in the shopping behavior of the variety of customers in their database. They assume they can't target everyone with the same methods, and instead would like to target different customers with an applicable marketing campaign. This exploratory analysis will inform what this strategy might look like to ensure Instacart targets the right customer profiles with the appropriate products.

## KEY QUESTIONS
1. What are the **busiest days** of the week and **hours** of the day?
2. Are there times of the day when people spend the most money?
3. How can we simplify the **price range groupings**?
4. Are there certain **types of products** that are more popular than others?
5. What’s the **distribution** among users in regards to their **brand loyalty**?
6. Are there differences in **ordering habits** based on a customer’s **loyalty status**?
7. Are there differences in **ordering habits** based on a **customer’s region**?
8. Is there a connection between **age and family status** in terms of **ordering habits**?
9. What different **classifications** does the demographic information suggest?
10. What differences can you find in **ordering habits of different customer profiles**?

<p align="center">
<img src="04. Analysis/By Profile/cluster_profile_top_depart.png" width=48%>      <img src="04. Analysis/hist_orders_frequency_hod.png" width=48%>
</p>

## CONTENTS
1. Project Management
     * Project Brief
2. Data: _Data is not uploaded due to their large size_
     * Original Data
     * Prepared Data
3. Scripts: Jupyter notebooks containing all code
4. Analysis: Data Profile Report

_Data wrangling/cleaning and analysis steps are all documented in the scripts_


## DATA
Instacart open-source data sets used:
* orders
* products
* departments
* orders_products_prior
* customers

The full details of the data are available **[here]([https://s3.amazonaws.com/coach-courses-us/public/courses/data-immersion/A4/A4_Data_Assets/customers.zip](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies))**


## TOOLS
For this project, the following Python libraries were used:
* pandas - for data analysis
* numpy - for mathematical equations
* matplotlib + seaborn - for visualization
* scipy - for data equations


## NOTES
Instacart is a real company that has made their data available offline. The contents of this project brief were fabricated for educational purposes by CareerFoundry.

"The Instacart Online Grocery Shopping Dataset 2017”, was accessed from [Kaggle](https://www.instacart.com/datasets/grocery-shopping-2017) on June 1, 2024
