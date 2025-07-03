
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

## Reflection
This project demonstrated the application of linear regression to a healthcare problem involving continuous outcome prediction. Simulating missing features highlighted the importance of feature engineering. The model showed a reasonable fit, but incorporating additional variables could improve accuracy. Visualization tools were critical for interpreting both data and model performance. This project strengthened my understanding of regression modeling and data preprocessing in a real-world context.


---

Feel free to reach out for questions or improvements!

