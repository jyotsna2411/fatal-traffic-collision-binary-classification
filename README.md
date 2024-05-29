# Traffic Collision Fatality Prediction

This project focuses on predicting whether a traffic collision event in Toronto would result in a fatality using machine learning models.

## Dataset
The dataset contains information on traffic collision events in Toronto from 2006 to 2022, with a focus on incidents where a person was killed or seriously injured (KSI). The dataset comprises various features including location, time, road conditions, vehicle types, and more.

## Exploratory Data Analysis (EDA)
1. **Data Understanding**: Explored the dataset to understand the features, their data types, and missing values. Visualized the distribution of the target variable to address class imbalance and gain insights.

2. **Statistical Analysis**: Conducted statistical analysis on numerical columns to identify patterns and trends in the data.

3. **Categorical Variables**: Analyzed the unique categories and frequency distribution of categorical variables to understand their impact on the target variable.

## Data Cleaning
1. **Handling Duplicates**: Identified and removed duplicate records from the dataset to ensure data integrity.

2. **Handling Missing Values**: Addressed missing values by applying appropriate imputation techniques or removing rows/columns as necessary.

3. **Data Transformation**: Transformed categorical variables using one-hot encoding and numerical features were scaled for model compatibility.

## Machine Learning Pipeline
1. **Feature Engineering**: Created new features and transformed existing ones to improve model performance.

2. **Model Selection**: Used the following algorithms for binary classification:
   - XGBoost
   - LightGBM
   - CatBoost 

3. **Evaluation Metrics**: Assessed model performance using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC to evaluate model effectiveness.

4. **Hyperparameter Tuning**: Optimized the hyperparameters of selected models using techniques like grid search or random search to enhance model performance.



For a detailed view of the analysis, refer to the Jupyter Notebook and the dataset utilized in this project.
