# Fake News Detection 

## Table of Contents:
* [Introduction](#introduction)
* [Objectives](#objectives)
* [Dataset](#dataset)
* [Analysis Approach](#analysis-approach) 
* [Conclusion](#conclusion) 
* [Technologies Used](#technologies-used)
* [References](#references)
* [Contact Information](#contact-information)

## Introduction:  
<div align="justify">This repository contains the code to build fake news detection model. Fake news detection has been a tremendously challenging problem that affects real-world politics and information propagation. The fact that content spreads so quickly and easily suggests that people (and algorithms behind the platforms) are potentially vulnerable to misinformation, be it accidental or intentional. Despite systematic efforts and fact-checking against misinformation, fake news still persists, leading people to see and share misleading information.</div>

## Objective:  
<div align="justify">
The main objective of this project is to build fake news detection system using various machine learning models. The models included in this study are:
•	Logistic Regression
•	Decision Tree Classification
•	Gradient Boosting Classifier
•	Random Forest Classifier
 </div>

## Dataset:  
<div align="justify">The dataset contains two types of articles: fake and real news. This dataset was collected from real-world sources. The truthful articles were obtained by crawling articles from Reuters.com, a news website. The fake news articles were collected from different sources, including unreliable websites flagged by PolitiFact (a fact-checking organization in the USA) and Wikipedia.
The dataset contains different types of articles on various topics, with the majority focusing on political and world news.</div><br>

**The dataset consists of two CSV files:** 
- True.csv
- Fake.csv

**Each article contains the following information:**<br>
- **Title:** The title of the article.
- **Text:** The full text of the article
- **Subject:** The subject of the article
- **Date:** The date the article was published<br>

<div align="justify">The data was collected primarily from 2016 to 2017. The collected data was cleaned and processed, but the punctuations and mistakes that existed in the fake news were kept in the text.</div>

## Analysis Approach:    
<div align="justify">To tackle this problem effectively, I have established a structured data analysis approach. <br>

- **Data Preprocessing:** Clean and preprocess the data, ensuring that text data is ready for model training
- **Model Training:** Train multiple models (Logistic Regression, Decision Tree Classification, Gradient Boosting Classifier, Random Forest Classifier) on the dataset
- **Evaluation:** Evaluate the performance of each model using appropriate metrics
- **Comparative Analysis:** Provide a comprehensive analysis comparing the performance of each model
 </div>

 ## Conclusion: 
 <div align="justify"> This project aims to provide insights into the effectiveness of different models for fake news detection. By comparing the performance of various models, I hope to contribute to the ongoing efforts to combat misinformation and improve the reliability of information dissemination.</div>

## Technologies Used:
- Python, version 3 
- NumPy for numerical computations
- Matplotlib and seaborn for data visualization
- Pandas for data manipulation
- Statsmodels for statistical modeling
- Sklearn for machine learning tasks
- Jupyter Notebook for interactive analysis

## References:
- Python documentations
- Python Regex (Regular Expressions)
- Stack Overflow
- Kaggle
- Medium documentations
- Deeplearning.ai

## Contact Information:
Created by https://github.com/Erkhanal - feel free to contact!
