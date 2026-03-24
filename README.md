 **Red Wine Quality Prediction:**
 
End-to-End Machine Learning Project for Predicting Wine Quality

**Project Overview:**

This project focuses on building a robust machine learning model to predict the quality of red wine based on its physicochemical properties. Wine quality assessment is traditionally performed by human experts, which can be subjective and inconsistent. This project aims to provide a data-driven, objective approach using machine learning techniques.

The system analyzes various chemical attributes of wine and predicts its quality score, enabling faster and more consistent evaluation. The project demonstrates a complete machine learning pipeline, from data preprocessing to model deployment using an interactive interface.

**Objectives:**

1. To analyze the relationship between chemical properties and wine quality

2. To build a predictive machine learning model with reliable accuracy

3. To create an interactive interface for real-time predictions

4. To ensure reproducibility of results for consistent evaluation

**Dataset Description**

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

**Methodology**

1. **Data Preprocessing:**
   
Handled missing values (if any)

Checked data distributions and outliers

Normalized/standardized features where required

Split dataset into training and testing sets


2.**Exploratory Data Analysis (EDA)**

Visualized feature distributions using histograms

Used correlation heatmaps to identify relationships

Analyzed impact of key features (like alcohol and acidity) on quality

3. **Model Selection**
**A Random Forest Classifier was chosen due to:**

High accuracy for structured/tabular data

Ability to handle non-linear relationships

Robustness against overfitting

4.**Model Training & Evaluation**

Trained the model on the training dataset

Evaluated using accuracy score and prediction outputs

Achieved an accuracy of approximately 70%

**Results:**

Model Performance
Accuracy: 0.70
The model performs reasonably well in predicting wine quality classes

**Sample Predictions:**

| Fixed Acidity | Volatile Acidity | Alcohol | Predicted Quality |
| ------------- | ---------------- | ------- | ----------------- |
| 7.4           | 0.7              | 9.4     | 5                 |
| 7.8           | 0.88             | 9.8     | 5                 |
| 7.9           | 0.6              | 10.5    | 6                 |

**Technologies Used:**
1. Python – Core programming language

2. Pandas – Data manipulation and preprocessing

3. NumPy – Numerical computations

4. Scikit-learn – Machine learning model building

5. Matplotlib & Seaborn – Data visualization

6. ipywidgets – Interactive UI components in notebook

**Interactive Features:**

One of the key highlights of this project is the interactive user interface built using widgets:

🔹 Single Prediction
Users can adjust sliders for input features
Instantly get predicted wine quality
🔹 Batch Prediction
Input multiple wine samples
Predict quality for all entries at once
This makes the project user-friendly and demonstrates practical deployment concepts.

**How to Run the Project**

1. Open the notebook file:Red_Wine_Quality_Prediction.ipynb

2. Upload it to Google Colab

3. Run all cells sequentially
   
Use:

Slider interface for single predictions,Batch UI for multiple predictions

**Reproducibility:**

1. The model produces consistent results across runs
   
2. Random states are fixed to ensure reproducibility
 
3. Same dataset and code will yield identical outputs

Future Improvements:

1. Improve model accuracy using advanced algorithms (XGBoost, Gradient Boosting)
   
2. Perform hyperparameter tuning
   
3. Deploy the model as a web application using Flask or Streamlit
   
4. Integrate real-time dataset input
   
5. Apply deep learning techniques for enhanced performance

**Conclusion:**

This project successfully demonstrates the application of machine learning in predicting wine quality. It highlights the importance of data preprocessing, feature analysis, and model selection in building an effective predictive system. The addition of an interactive interface further enhances usability and practical relevance.

**Project Link:**

GitHub Repository:
👉 https://github.com/Suhasperumalla5004/Red-Wine-Quality-Prediction







