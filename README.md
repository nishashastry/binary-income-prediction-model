# Binary Income Stacking Ensemble
This notebook creates a stacking ensemble model to predict whether an adult makes > $50K and year or <= $50K a year

## Data Inspection
The adult census dataset contains features including age, workclass, gender, occupation, location, etc.
The chosen label is whether an adult's income is > 50K or <=50K.

## Data Cleaning
### Replacing Null Values
Replaced numerical null values with the respective feature's mean, categorical null values with the mode.
### Further Data Processing
Techniques used: windsorization, one-hot encoding (for categorical features), replacing outliers, renaming features

## Statistics
Used seaborn and matplotlib libraries for statistcal calculation and visauls for correlation analysis. This is also where any class imbalances were detected and addressed

## Model Selection
Models used: KNN, Decision Trees, Linear Regression, Random Forest. Hypterparamter defining and tuning occurs at this stage. The stacking ensemble is then trained on the adult census dataset on a 80/20 split
