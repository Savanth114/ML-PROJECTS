# ML-PROJECTS
# Cognifyz Machine Learning Internship – Task 1 & 2 Submission

### Intern: Savanth G  
**B.Tech CSE (AIML)**  
Presidency University, Bengaluru  
Internship Period: 9 June 2025 - 9 july 2025 

---

## Overview

This repository contains the completed **Task 1 and Task 2** of the **Machine Learning Internship** offered by **Cognifyz Technologies**. These tasks focus on **restaurant rating prediction** and a **content-based restaurant recommendation system**, combining data preprocessing, machine learning models, and user-centric design.

---

##  Task Summary

###  Task 1: Restaurant Rating Prediction

- **Objective**: Predict the **aggregate rating** of restaurants using various features such as price range, votes, and location.
- **Steps Covered**:
  - Data cleaning and missing value handling
  - Encoding categorical features using `get_dummies`
  - Model training with:
    - `RandomForestRegressor`
    - `LinearRegression`
  - Model evaluation using:
    - R² Score
    - Mean Squared Error (MSE)
  - Feature importance analysis for interpretability

---

###  Task 2: Restaurant Recommendation System

- **Objective**: Build a **content-based filtering system** that recommends restaurants based on user preferences.
- **Features Used**:
  - Cuisine type
  - Price range
  - Rating threshold
  - Delivery availability
  - City and currency filters
- **Workflow**:
  - Label encoding of user filters
  - Text vectorization using `TfidfVectorizer`
  - Similarity matching using `CosineSimilarity`
  - Dynamic user input handled with validations and defaults
- **Output**: A sorted table of the **top 10 recommended restaurants** matching user-defined criteria.

---

##  Tools & Libraries Used

- Python, pandas, numpy  
- scikit-learn  
- TfidfVectorizer, LabelEncoder  
- Google Colab

---

##  File Structure

ML-PROJECTS/
├──Task1_Rating_Prediction.ipynb
├──Task2_Recommendation_System.ipynb
├──Dataset.csv
└── README.md

## Contact

**Savanth G**  
📧 savanthg14@gmail.com  
🌐 LinkedIn : linkedin.com/in/savanth-g-65454a36b
