# Jamboree Productions - Open Exploratory Analysis
<p align="center">
  <img width="614" alt="Screenshot 2024-07-20 at 2 31 08 PM" src="https://github.com/user-attachments/assets/4a4f139f-9c70-4a29-a62f-c972f58f9fa7">
</p>
<h3 align="center">
  Film market analysis to determine production strategy for future films
</h3>

## CONTEXT
Jamboree Productions is an emerging film production company that wants to take a data-driven approach to developing new film ideas. Using the comprehensive film database from The Movie Database (TMDB), they would like to predict both revenue and viewer rating by analyzing the qualities of all films in the database. While the key results will be made available on a Tableau dashboard, additional analysis will be stored in GitHub.

## KEY QUESTIONS
1. What factors predict a film's success in terms of **revenue and vote average**?
2. **How strong are the correlations** between budget and runtime with revenue and vote average?
3. Which genres **overperform at the box office**?
4. Which other production companies are making the most successful films?
5. Are similar films able to be divided into groups?
6. Are there any emerging trends in these factors that could influence a film's success?

<p align="center">
<img width="1334" alt="Screenshot 2024-07-27 at 10 31 08 AM" src="https://github.com/user-attachments/assets/dbf34d85-3024-4327-9cee-79afd1a51f4e">      <img src="04. Analysis/hist_orders_frequency_hod.png" width=48%>
</p>

## CONTENTS
1. Project Management
     * Project Brief
2. Data: _Data is not uploaded due to their large size_
     * Original Data
     * Prepared Data
3. Scripts: Jupyter notebooks containing all code
     * Cleaning the Dataset
     * Expanding Variables
     * Exploring Relationships
     * Geographical Visualizations
     * Sourcing & Analyzing Time Series Data
     * Supervised Machine Learning
     * Unsupervised Machine Learning
4. Analysis: Data Profile Report


## DATA
Founded in 2008, The Movie Database (TMDB) is a comprehensive collection of 1,000,000+ movies including information about the movies' title, genre, ratings, release date, budget, etc. Data is sourced from website members around the world. However, this opens the dataset up to bias and error. The majority of time spent on any analysis with this data should be on cleaning the dataset

**Common issues with the data:**
* films had too much missing data
* tv shows and short films (<40min) were listed in the same category as feature films
* budget and revenue information does not require any proof upon reporting
* there is no standardization on how production companies are listed
* the popularity metric is biased towards recent releases
* TMDB was founded in 2008, so there are many films from before this time that are not included

The full details of the data are available **[here](https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies)**


## TOOLS
For this project, the following Python libraries were used:
* pandas - for data analysis
* numpy - for mathematical equations
* matplotlib + seaborn - for visualization
* scipy - for data equations
* folium + json - geographic visualizations
* sklearn - supervised/unsupervised machine learning

