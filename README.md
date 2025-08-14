# Student-Performance-Prediction-using-Machine-Learning-

## Project Overview
 - This project aims to predict student performance based on various academic and socio-economic factors using Python’s machine learning and data analysis libraries.

 - The workflow involves Exploratory Data Analysis (EDA), feature engineering, model training, and evaluation.

 - By predicting student scores, we can identify key factors influencing performance and suggest actionable interventions.

### Objectives
 - Perform EDA to understand relationships between features and student scores.

 - Preprocess data: handle missing values, encode categorical variables, and scale features.

 - Train regression models to predict student performance.

 - Evaluate models using error metrics and statistical scores.

 - Interpret model coefficients to understand feature importance.

### Tech Stack
The dataset contains multiple features representing:

 - Demographics: Gender, parental education level

 - Study-related habits: Test preparation course, study time

 - Academic scores: Math, Reading, Writing scores

 - The target variable is the final student performance score.

### Methodology
1. Data Loading & Inspection

 - Loaded the dataset into a pandas DataFrame.

 - Checked data types, missing values, and basic statistics.

2. Exploratory Data Analysis (EDA)

 - Plotted distributions of scores using Seaborn.

 - Created helper functions for reusable plotting.

 - Analyzed relationships between categorical features and performance.

3. Feature Engineering

 - Encoded categorical variables (pd.get_dummies).

 - Applied feature scaling where necessary.

4. Model Training

 - Split data into train and test sets.

 - Trained a Linear Regression model.

5. Model Evaluation

 - Mean Absolute Error (MAE): Measures average absolute prediction error.

 - R² Score: Measures proportion of variance explained by the model.

 - Model Coefficients: Interpreted to understand the influence of each feature

### Key Results

 - MAE provided an intuitive measure of average prediction error in the same units as the target score.

 - R² Score indicated how much variance in performance was explained by the model.

 - Model Coefficients revealed which factors positively or negatively impacted student scores.

