# Binary Income Stacking Ensemble
This app creates and trains a stacking ensemble model containing logistic regression, random forest, decision trees, and KNNs. It is trained on an adult census dataset to predict whether an adult makes > $50K and year or <= $50K a year

## Data Inspection
The adult census dataset contains features including age, workclass, gender, occupation, location, etc.
The chosen labels the income > 50K or <=50K.

## Data Cleaning
### Replacing Null Values
Replaced numerical null values with the respective feature's mean, categorical null values with the mode.
### Further Data Processing
Techniques used: windsorization, one-hot encoding (for categorical features), replacing outliers, renaming features

## Statistics
Used seaborn and matplotlib libraries for statistcal calculation and visauls for correlation analysis. This is also where any class imbalances were detected and addressed

## Model Selection
Models used: KNN, Decision Trees, Linear Regression, Random Forest. Hypterparamter defining and tuning occurs at this stage.
