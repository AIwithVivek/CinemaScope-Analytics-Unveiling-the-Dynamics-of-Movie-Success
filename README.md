---

<h1 align="center">IMDb Movie Analysis Using Excel</h1>

<p align="center"> 
<img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExNzY0bWdoNXNrM2Rkdnp5eTU1bDJlMGFlenpsbDA2NnJnYWVraW50ZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/zqLApNj9FopviA4LAc/giphy.webp" alt="divider" width="300">
</p>

| **Sections**                                                                        |
|-------------------------------------------------------------------------------------|
| [Introduction](#1-introduction)                                                     |
| [Data Source](#2-data-source)                                                       |
| [Data Cleaning and Excel Formulas](#3-data-cleaning-and-excel-formulas)           |
| [Dashboard Overview](#4-dashboard-overview)                                         |
| [Key Insights and Data Storytelling](#5-key-insights-and-data-storytelling)         |
| [Conclusions](#6-conclusions)                                                       |

<p align="center"> 
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" alt="divider">
</p>

## **1. Introduction**

The primary objective of analyzing the **IMDb movie dataset** is to uncover the factors that contribute to a movie's success, focusing on attributes such as **directors, genres, budgets, ratings**, and **box office performance**. This analysis aims to provide insights that can assist filmmakers, producers, and investors in making informed decisions.

---

## **2. Data Source**

The analysis utilizes the `movies.csv` dataset, which includes vital information about various movies:

- **name**: Movie title
- **rating**: Age rating (e.g., PG-13, R)
- **genre**: Genre classification
- **year**: Release year
- **score**: IMDb rating
- **votes**: Number of IMDb votes
- **director**: Name of the director
- **budget**: Production budget
- **gross**: Box office revenue
- **runtime**: Duration in minutes
- **country**: Country of origin
- **company**: Production company

---

## **3. Data Cleaning and Excel Formulas**

### **Data Cleaning Process**:
- Handled **missing values** by filling essential fields like budget and ratings.
- Ensured categorical data consistency for directors and genres.

### **Excel Formulas Used**:
- **IF Statements** for categorizing IMDb scores into **High**, **Medium**, and **Low**.
- **VLOOKUP** and **INDEX-MATCH** to retrieve related details.
- **SUMIFS** and **COUNTIFS**,etc for aggregating movie counts by genres and directors.
- **Conditional Formatting** to highlight high-budget films.
- **Statistical** operations were performed to find statistical insights  

---

## **4. Dashboard Overview**

### **IMDb Movie Analysis Dashboard**
- This **interactive Excel dashboard** presents key insights into movie data, showcasing trends in genres, director performance, and budget comparisons.
 
![IMDb Movie Analysis Dashboard](https://github.com/AIwithVivek/CinemaScope-Analytics-Unveiling-the-Dynamics-of-Movie-Success/blob/main/genre%20analysis.PNG?raw=true)

### **Top Directors and Star Analysis**
- An Interactive Dashboards showing top directors and actors across different genres and ratings .

![Top Directors Analysis](https://github.com/AIwithVivek/CinemaScope-Analytics-Unveiling-the-Dynamics-of-Movie-Success/blob/main/director%20and%20star%20analysis.PNG?raw=true)


## **5. Key Insights and Data Storytelling**

The analysis revealed important insights, including:

- The analysis reveals valuable insights for Hollywood Insights Inc. and its clients, such as:

- Genre Trends: Certain genres like Action and Adventure tend to generate higher box office revenue, while niche genres maintain steady audiences. Director Impact: Top directors consistently produce high-grossing movies, indicating the importance of directorial influence on box office success. Profitability Trends: Larger budgets do not always guarantee higher profitability, with many low-budget films yielding high returns. Seasonal Patterns: There are clear trends in the timing of movie releases, with certain months and seasons showing higher box office activity.

---

## **6. Conclusions**

This analysis of the **IMDb movie dataset** highlights key factors that contribute to a movie's success. By examining director influence, genre trends, and the relationship between budget and ratings, stakeholders can make informed decisions regarding production and marketing strategies.

The interactive dashboard enables users to explore data dynamically, providing a comprehensive understanding of what drives a movie's success.

---

**Explore the complete dashboard [here](https://docs.google.com/spreadsheets/d/1VqPVj6b0-WCyzqpSWC-4eMEahsvjbaFh/edit?usp=drive_link&ouid=113169878008296474979&rtpof=true&sd=true)**
