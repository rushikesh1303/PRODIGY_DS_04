# PRODIGY_DS_04

---

## Task 4: Sentiment Analysis on Social Media Data

This repository contains **Task 04** of the **Prodigy InfoTech Data Science Internship**.

---

## Problem Statement

Analyze and visualize **sentiment patterns** in social media data to understand public opinion and attitudes towards specific topics or brands. The objective is to build a machine learning model that can classify text into sentiment categories such as Positive, Negative, and Neutral.

---

## Dataset

The dataset used in this task is a **Twitter-based Social Media Sentiment Dataset** provided by Prodigy InfoTech.

It includes data such as:

- Tweet ID  
- Entity/Topic  
- Sentiment Label (Positive, Negative, Neutral)  
- Tweet Text  

The target variable represents the **sentiment expressed in each tweet**.

---

## Work Done

- Loaded and explored the social media sentiment dataset  
- Performed **text preprocessing**:
  - Lowercasing text  
  - Removing URLs, mentions, hashtags, and special characters  
  - Removing stopwords  
- Converted text into numerical features using **TF-IDF Vectorization**  
- Encoded sentiment labels into numeric values  
- Split dataset into **training and testing sets**  
- Trained a **Logistic Regression classifier** for sentiment prediction  
- Evaluated model performance using:
  - Accuracy  
  - Confusion Matrix  
  - Classification Report  
- Visualized sentiment distribution and classification performance  
- Built a custom function to predict sentiment of new user input  

---

## Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- NLTK  
- Jupyter Notebook
