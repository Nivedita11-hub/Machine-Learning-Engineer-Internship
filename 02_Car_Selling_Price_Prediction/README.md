# Car Selling Price Prediction

Machine Learning Engineer Internship — Intermediate Task.

## Objective

Build a machine learning regression model to predict the approximate selling price of a used car based on its features.

## Dataset

The dataset contains information about used cars, including:

- Present Price
- Kilometres Driven
- Owner
- Fuel Type
- Seller Type
- Transmission
- Year

## Data Preprocessing

The following preprocessing steps were performed:

- Calculated the years of service of each car from its year.
- Removed unnecessary columns.
- Separated numerical and categorical features.
- Applied StandardScaler to numerical features.
- Applied OneHotEncoder to categorical features.
- Used a machine learning pipeline to combine preprocessing and model training.

## Model Used

Random Forest Regressor was used to predict the selling price.

The dataset was divided into:

- 80% training data
- 20% testing data

## Model Performance

The model achieved the following results on the test dataset:

| Metric | Score |
|---|---:|
| R² Score | 0.9621 |
| MAE | 0.6218 |
| RMSE | 0.9342 |

## Conclusion

The project successfully implements a complete machine learning regression workflow for predicting used car selling prices. The model achieved an R² score of 0.9621 on the test dataset, showing strong predictive performance for this dataset and train-test split.
