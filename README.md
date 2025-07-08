# ML-PROJECTS
# Cognifyz Machine Learning Internship – Task 1 to 4 Submission

### Intern: Savanth G  
**B.Tech CSE (AIML)**  
Presidency University, Bengaluru  
Internship Period: 9 June 2025 - 9 july 2025 

---

## Overview

This repository contains the completed Task 1, Task 2, Task 3, and Task 4 of the Machine Learning Internship offered by Cognifyz Technologies. These tasks involve building intelligent ML systems for restaurant data: including rating prediction, recommendation engines, cuisine classification, and sentiment analysis. Each task demonstrates hands-on use of data preprocessing, machine learning models, NLP, and performance evaluation.
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

### Task 3: Cuisine Classification

- **Objective**: Classify restaurants into **cuisine categories** using supervised classification algorithms.
- **Steps Covered**:
  - Data preprocessing: handling missing values & encoding categorical variables
  - Train-test split
  - Model training with:
    - `RandomForestRegressor`
    - `LinearRegression`
- **Evaluation using**:
  - Accuracy
  - Precision
  - Recall
  - Addressed class imbalance and analyzed model performance across cuisine categories

---

### Task 4: Sentiment Analysis on Restaurant Reviews

- **Objective**: Analyze the sentiment (positive/negative) of customer reviews using Natural Language Processing (NLP).
- **Steps Covered**:
  - Text cleaning: punctuation removal, stopword removal, lowercase conversion
  - Tokenization and lemmatization
  - Feature extraction using TfidfVectorizer
  - Model training with:
    - `LogisticRegression`
    - `MultinomialNB`
- **Evaluation using**:
  - Accuracy
  - Confusion Matrix
  - Classification Report
- **Output**: Classifies reviews as Positive or Negative. Includes sentiment prediction for both batch data and custom inputs.

---

##  Tools & Libraries Used

- Python, pandas, numpy  
- scikit-learn, NLTK/spaCy
- TfidfVectorizer, LabelEncoder  
- Google Colab

---

##  File Structure

ML-PROJECTS/
- Task1_Rating_Prediction.ipynb
- Task2_Recommendation_System.ipynb
- Task3_Cuisine_Classification.ipynb
- Task4_Sentiment_Analysis.ipynb
- Dataset.csv
- README.md

## Contact

**Savanth G**  
📧 savanthg14@gmail.com  
🌐 LinkedIn : linkedin.com/in/savanth-g-65454a36b
