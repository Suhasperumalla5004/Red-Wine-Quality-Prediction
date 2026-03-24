## Student Performance Analysis and Grade Prediction using Machine Learning

Perumalla Sai Suhas

GitHub Link:

https://github.com/Suhasperumalla5004/Red-Wine-Quality-Prediction

## Abstract

This project presents a data-driven approach to analyzing student academic performance and predicting final grades using machine learning techniques. The study focuses on key behavioral factors such as self-study hours, attendance, and class participation to understand their impact on academic outcomes.

A large-scale dataset consisting of approximately one million records was analyzed using exploratory data analysis and statistical methods to identify significant patterns. Two machine learning models, Logistic Regression and Random Forest, were implemented to classify student performance into grade categories.

The results indicate that behavioral factors play a crucial role in predicting academic success, with self-study hours emerging as the most influential feature. The Random Forest model demonstrated superior predictive performance, while Logistic Regression provided interpretability.

This project was independently developed as a self-initiated effort to strengthen practical skills in machine learning and data analysis.


## Project Overview:

This project focuses on building a robust machine learning model to predict the quality of red wine based on its physicochemical properties. Wine quality assessment is traditionally performed by human experts, which can be subjective and inconsistent. This project aims to provide a data-driven, objective approach using machine learning techniques.

The system analyzes various chemical attributes of wine and predicts its quality score, enabling faster and more consistent evaluation. The project demonstrates a complete machine learning pipeline, from data preprocessing to model deployment using an interactive interface.

**Objectives:**

1. To analyze the relationship between chemical properties and wine quality

2. To build a predictive machine learning model with reliable accuracy

3. To create an interactive interface for real-time predictions

4. To ensure reproducibility of results for consistent evaluation

## Dataset Description

The dataset used in this project contains multiple physicochemical features of red wine samples, such as:

1. Fixed Acidity
   
2. Volatile Acidity

3. Citric Acid
   
4. Residual Sugar
   
5. Chlorides

6. Free Sulfur Dioxide
   
7. Total Sulfur Dioxide
   
8. Density

9. pH

 10. Sulphates

 11. Alcohol

The target variable is wine quality, typically rated on a scale from 0 to 10.

## Data Preprocessing

* The dataset was preprocessed to ensure quality and consistency:

* Removed irrelevant columns such as student identifiers

* Eliminated leakage-prone features to maintain model integrity

* Checked and confirmed absence of missing values

* Converted categorical grade labels into numerical format

* Prepared dataset for machine learning model training

These steps ensured that the dataset was clean and suitable for analysis.

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis was conducted to understand the distribution and relationships between variables.

**Key observations include:**

* Higher self-study hours are strongly associated with better grades

* Attendance percentage shows a positive correlation with performance

* Students with higher participation scores tend to perform better academically

Visualization techniques such as box plots, histograms, and correlation analysis were used to support these findings. The insights obtained from EDA guided the model selection and feature importance analysis.

## Machine Learning Models

Two machine learning models were implemented:

**Logistic Regression**

* Used as a baseline classification model

* Provides high interpretability

Helps understand feature influence

**Random Forest Classifier**

* Ensemble learning method

* Captures complex and non-linear relationships

* Provides improved prediction accuracy

## Model Evaluation

Model performance was evaluated using standard classification metrics:

* Accuracy

* Precision

* Recall

* F1-score

The Random Forest model achieved higher predictive accuracy compared to Logistic Regression. However, Logistic Regression provided better interpretability, making it useful for understanding feature contributions.

## Feature Importance

Feature importance analysis revealed the following:

1.Weekly self-study hours – most significant factor

2.Attendance percentage – strong influence

3.Class participation – contributes to overall performance

These findings are consistent with the patterns observed during exploratory data analysis.

## Key Insights

* Self-study is the most critical factor influencing student success

* Regular attendance significantly improves academic outcomes

* Classroom engagement positively impacts performance

* Behavioral data alone is sufficient to build effective predictive models


## Tools and Technologies

The project was developed using a combination of programming tools, data analysis libraries, and machine learning frameworks to ensure an efficient and reproducible workflow.

**Programming Language:**
**Python** was used as the primary programming language due to its extensive support for data analysis and machine learning.

**Data Manipulation and Analysis:**
**Pandas and NumPy** were utilized for efficient data handling, preprocessing, and numerical computations on large-scale datasets.

**Data Visualization:**
**Matplotlib and Seaborn** were used to perform exploratory data analysis and generate visual representations such as histograms, box plots, and correlation heatmaps to identify patterns and trends.

**Machine Learning Framework:**
**Scikit-learn** was used for implementing classification models such as Logistic Regression and Random Forest, along with model evaluation and performance metrics.

**Development Environment:**
**Jupyter Notebook** was used to develop and document the project in an interactive manner, enabling step-by-step execution, visualization, and explanation of results.

**Version Control and Code Management:**
**GitHub** was used to manage the project repository, maintain version control, and ensure reproducibility and transparency of the implementation.

## Future Improvements

1. Improve model accuracy using advanced algorithms (XGBoost, Gradient Boosting)
   
2. Perform hyperparameter tuning
   
3. Deploy the model as a web application using Flask or Streamlit
   
4. Integrate real-time dataset input
   
5. Apply deep learning techniques for enhanced performance

## Conclusion:

This project demonstrates how machine learning can be applied to analyze and predict student performance using behavioral data. By integrating data analysis with predictive modeling, the study provides a structured and objective approach to academic evaluation.

The findings highlight the importance of data-driven decision-making in education and showcase the potential of machine learning in improving academic systems.

## Project Repository

In addition to this project, a related machine learning project demonstrating similar concepts of data preprocessing, feature engineering, and predictive modeling is available on GitHub:

👉 https://github.com/Suhasperumalla5004/Red-Wine-Quality-Prediction

 The project focuses on predicting wine quality using physicochemical attributes and applies machine learning techniques including data cleaning, model training, and performance evaluation.
 
This repository reflects my hands-on experience in implementing end-to-end machine learning workflows and my ability to apply theoretical concepts to real-world datasets. It also demonstrates my initiative in continuously developing practical skills through self-driven projects.









