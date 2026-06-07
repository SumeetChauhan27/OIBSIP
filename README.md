# 🌟 Oasis Infobyte Data Science Internship (OIBSIP)

Welcome to my Data Science Internship repository! This repository contains all the projects I completed during my internship with **Oasis Infobyte**. 

**Intern:** Sumeet Kailash Chauhan  
**Domain:** Data Science  
**Batch:** June 2026  

---

## 📚 General Overview
During this internship, I developed five distinct machine learning and data analysis projects. My primary goal was to write clean, beginner-friendly Python code and to build a strong foundational understanding of Data Science concepts.

### 🛠️ Technologies Used Across All Tasks
- **Languages:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Data Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## 🚀 The Five Tasks

### [Task 1: Iris Flower Classification](./Task_1_Iris_Flower_Classification)
* **What I Used:** Random Forest Classifier.
* **Why I Used It:** The Iris dataset is a classic beginner problem. Random Forest handles categorical data beautifully and provides high accuracy with minimal hyperparameter tuning.
* **How I Did It:** I loaded the dataset, split it into training and testing sets, trained the Random Forest model, and evaluated it using an accuracy score and a confusion matrix.
* **What I Learned:** How to structure a basic machine learning pipeline, handle multiclass classification problems, and measure model performance using standard evaluation metrics.

### [Task 2: Unemployment Analysis](./Task_2_Unemployment_Analysis)
* **What I Used:** Pandas, Matplotlib, and Seaborn.
* **Why I Used It:** Unemployment data requires deep visual analysis rather than pure predictive modeling. Seaborn makes it very easy to visualize trends over time and compare different regions.
* **How I Did It:** I imported COVID-19 era unemployment data, cleaned up the missing values, grouped the data by geographic regions, and plotted bar charts and line graphs to observe the spikes in unemployment.
* **What I Learned:** Advanced data cleaning, grouping large datasets, and extracting actionable insights entirely through Exploratory Data Analysis (EDA) and visualization.

### [Task 3: Car Price Prediction](./Task_3_Car_Price_Prediction)
* **What I Used:** Random Forest Regressor.
* **Why I Used It:** Predicting car prices is a regression problem. Random Forest Regressor can capture non-linear relationships (like the complex connection between a car's age, its brand, and its price) very effectively.
* **How I Did It:** I engineered a new feature (`Car_Age`) from the `Year` column, converted text data into numbers using one-hot encoding (`get_dummies()`), and trained the model to predict the selling price.
* **What I Learned:** Feature engineering, handling categorical variables, and understanding regression metrics like Mean Absolute Error (MAE) and R-Squared.

### [Task 4: Email Spam Detection](./Task_4_Email_Spam_Detection)
* **What I Used:** Multinomial Naive Bayes & CountVectorizer.
* **Why I Used It:** Naive Bayes is incredibly fast and highly effective for text classification (NLP). `CountVectorizer` was necessary to convert human-readable text messages into numbers the model could understand.
* **How I Did It:** I removed messy unneeded columns, assigned binary labels (`1` for spam, `0` for ham), vectorized the text data based on word frequency, and fed it into the Naive Bayes classifier.
* **What I Learned:** Natural Language Processing (NLP) basics, text vectorization (bag-of-words), and discovering how real-world spam filters work under the hood.

### [Task 5: Sales Prediction](./Task_5_Sales_Prediction)
* **What I Used:** Linear Regression.
* **Why I Used It:** Sales predictions based on advertising budgets often follow linear patterns. Linear regression is the most transparent and simple model to understand these direct relationships.
* **How I Did It:** I analyzed the correlation between TV, Radio, and Newspaper budgets against the target variable (`Sales`). I then fit a Linear Regression line and visualized the actual vs. predicted sales on a scatter plot.
* **What I Learned:** Building and interpreting linear models, analyzing feature correlations, and using Mean Squared Error (MSE) to check the average error of my predictions.

---

## 🏁 Conclusion
This internship allowed me to solidify my foundation in Data Science, ranging from Exploratory Data Analysis (EDA) to Natural Language Processing (NLP) and Predictive Modeling. 

All code is fully documented and structured nicely inside the respective task folders in this repository. 

*Note: This repository and all tasks are intended for submission to the official Oasis Infobyte portal.*
