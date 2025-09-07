# Amazon Bestselling Books Analysis

This project analyzes the **top 100 Amazon bestselling books (2009–2021)** to uncover the key factors that contribute to a book becoming a bestseller. Using Python, Pandas, Seaborn, and Scikit-learn, the notebook provides both **exploratory data analysis (EDA)** and **predictive modeling**.

---

## Features

- **Data Cleaning & Preprocessing** – Handles missing values and encodes categorical variables.
- **Exploratory Data Analysis (EDA)**  
  - Distribution of genres and top authors  
  - Ratings vs reviews scatter plots  
  - Correlation heatmaps  
  - Trends of top 10 books by genre over the years
- **Predictive Modeling**  
  - Random Forest Classifier to predict whether a book will be a top 10 bestseller  
  - Model evaluation using ROC-AUC, classification report, and confusion matrix  
  - Feature importance visualization to understand key drivers of sales
- **Predictive Insights Table**  
  - Highlights top predicted books using model probabilities  
  - Beautiful, color-coded table for clear interpretation

---

## Tech Stack

- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## Dataset

The dataset contains information about Amazon’s top 100 bestselling books from 2009 to 2021, including:

- Rank  
- Title  
- Author  
- Genre  
- Ratings & number of reviews  
- Cover type  
- Price  
- Year of publication  
