# SCT_ML_1 - House Price Prediction

## Internship Task

Machine Learning Internship - SkillCraft Technology.

### Task 01

Implement a Linear Regression model to predict house prices based on
square footage, number of bedrooms, and number of bathrooms.

## Objective

The objective of this project is to build a machine learning regression
model that predicts house prices using selected house characteristics.

## Dataset

The project uses the House Prices dataset from Kaggle.

The following features were selected:

- GrLivArea - Above-ground living area in square feet
- BedroomAbvGr - Number of bedrooms
- FullBath - Number of full bathrooms

Target variable:

- SalePrice - House sale price

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Algorithm

Linear Regression was used for predicting house prices.

The dataset was divided into:

- 80% training data
- 20% testing data

## Model Evaluation

The model achieved the following results on the test dataset:

| Metric | Result |
|---|---:|
| MAE | 35,788.06 |
| MSE | 2,806,426,667.25 |
| RMSE | 52,975.72 |
| R² Score | 0.6341 |

The R² score indicates that approximately 63.41% of the variation in
house prices is explained by the selected features in this model.

## Results

The model can predict house prices based on living area, bedrooms,
and bathrooms.

An Actual vs Predicted visualization is included in the `results`
directory.

## Project Structure

```text
SCT_ML_1/
│
├── data/
├── notebooks/
│   └── house_price_prediction.ipynb
├── results/
│   └── actual_vs_predicted.png
├── README.md
├── requirements.txt
└── .gitignore
