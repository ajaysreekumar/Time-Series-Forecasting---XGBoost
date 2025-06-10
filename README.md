# NHS referral to Treatment Wait Time Analysis and Optimization

## Introduction
This project focuses on analyzing NHS patient treatment wait times using statistical and optimization techniques. The objective is to assess and improve the performance of NHS trusts against key national targets for 2025/26.

## Aim and Questions of Interest
- What are the current trends in NHS Referral to Treatment wait times?
- Can we identify key factors affecting delays?
- How can we optimize resource allocation to meet national targets?

## Libraries Used
- `matplotlib.pyplot`
- `XGBoost`
- `numpy`
- `optuna`
- `pandas`
- `seaborn`

## Data Preparation and Cleaning
Data was sourced from an Excel file and included cleaning steps such as:
- Reading the dataset into a DataFrame.
- Checking for null values and dropping irrelevant or missing entries.
- Selecting relevant columns for modeling.

## Exploratory Data Analysis
The analysis involved:
- Descriptive statistics to understand the dataset.
- Visualizations such as histograms and scatter plots to explore distributions and relationships.

## Modeling and Optimization
The modeling approach included:
- Hyperparameter tuning using Optuna for an XGBoost regressor.
- Evaluation of trial performances using cross-validation.
- Selection of the best parameters to reduce wait times.

## Results and Evaluation
The best model configuration was assessed using:
- R² score and RMSE to evaluate model accuracy.
- Visualization of model predictions versus actual wait times.

## Conclusion
- A predictive model was built to identify factors impacting patient wait times.
- Optuna successfully optimized model parameters.
- The model can guide NHS trusts toward achieving treatment targets.

## Limitations
- The model is limited to the features available in the dataset.
- External factors (e.g., policy changes, seasonal trends) were not considered.
- Further validation with unseen data is necessary.

## Further Analysis
- Incorporate time-series modeling for temporal patterns.
- Add external datasets (e.g., staffing levels, regional demographics).
- Develop a decision-support tool to simulate policy impacts.
