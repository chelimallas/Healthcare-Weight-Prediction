
# Healthcare Weight Prediction Using Linear Regression

## Project Overview
This project focuses on predicting a person’s **weight** based on features such as **height**, **age**, and **exercise level** using a supervised machine learning approach—**Linear Regression**. Accurate weight prediction can support healthcare decision-making, personalized treatment, and wellness planning.

## Dataset
The dataset is sourced from [Kaggle - 500 Person Gender Height Weight BMI Dataset](https://www.kaggle.com/datasets/yersever/500-person-gender-height-weight-bodymassindex). It contains measurements of gender, height, weight, and BMI category. Since the dataset lacks some important predictors like age and exercise level, these features were simulated to enrich the analysis.

## Methodology
- Loaded and preprocessed the dataset, including simulating missing features.
- Encoded categorical variables (`Gender`, `Exercise`).
- Performed exploratory data analysis to understand feature relationships.
- Trained a Linear Regression model using `Height`, `Age`, and `Exercise` as predictors.
- Evaluated the model performance using Mean Squared Error (MSE) and R² Score.
- Visualized results and residuals to assess model fit.

## Results
| Metric                   | Value    |
|--------------------------|----------|
| Mean Squared Error (MSE) | *e.g., 100.75* |
| R² Score                 | *e.g., 0.693*  |

*Note: Replace the values above with your actual model results.*

## Reflection on the Problem and Solution

The goal of this project was to build a regression model to predict a person's weight using features like height, age, and exercise level. While the dataset provided by Kaggle included height and weight, it lacked important contextual features such as age and activity level. This challenge provided an opportunity to simulate those missing variables in a realistic way, reinforcing the value of feature engineering in data science.

Linear regression was chosen as the predictive model due to its simplicity and interpretability. After training the model and evaluating it using Mean Squared Error (MSE) and R² score, we found that the model was able to capture general trends in the data but left room for improvement. The visualizations (scatterplots, residual plots, correlation heatmaps) were particularly useful in understanding how well the model performed and in identifying potential limitations.

Overall, this project demonstrated a full machine learning workflow—from data preprocessing to model evaluation—within a healthcare context. It emphasized the importance of data quality, thoughtful feature creation, and performance visualization. In real-world applications, incorporating more detailed health indicators such as diet, sleep, or medical history could significantly improve model accuracy and utility.

