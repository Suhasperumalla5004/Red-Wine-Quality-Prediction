# Red Wine Quality Prediction 🍷
End-to-end machine learning project predicting red wine quality using chemical features.

## Features
- Data loading, preprocessing, and exploratory data analysis (EDA)
- Random Forest model training and evaluation
- Interactive UI in Google Colab for single and batch predictions
- Exact numeric predictions for reproducibility

## Example Outputs
- Model Accuracy: 0.70
- Example wine predictions:
| Fixed Acidity | Volatile Acidity | Alcohol | Predicted Quality |
|---------------|----------------|---------|-----------------|
| 7.4           | 0.7            | 9.4     | 5               |
| 7.8           | 0.88           | 9.8     | 5               |
| 7.9           | 0.6            | 10.5    | 6               |

## Technologies
- Python
- Pandas
- Scikit-learn
- ipywidgets
- Matplotlib / Seaborn

## How to Run
1. Open `Red_Wine_Quality_Prediction.ipynb` in Google Colab.
2. Run all cells sequentially.
3. Use the sliders to predict the quality of a single wine.
4. Use the batch prediction UI to predict multiple wines at once.

## Notes
- All outputs are reproducible; running the notebook again gives the same results.
- PDF version of the notebook is included for review.
