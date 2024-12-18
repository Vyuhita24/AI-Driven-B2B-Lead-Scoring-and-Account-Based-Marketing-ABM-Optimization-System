# Sales Prediction Using Linear Regression

## Overview
This project demonstrates the use of linear regression to predict sales based on advertising budgets for various channels, such as TV, radio, and newspapers. The aim is to understand the relationship between the advertising expenses and sales, and to create a model that can make accurate predictions.

## Dataset
The dataset used in this project includes the following features:
- **TV**: Advertising budget for TV (in thousands of dollars).
- **Radio**: Advertising budget for radio (in thousands of dollars).
- **Newspaper**: Advertising budget for newspapers (in thousands of dollars).
- **Sales**: Sales generated (in thousands of units).

## Project Structure
- **`sales_prediction.ipynb`**: Jupyter Notebook containing the entire analysis and implementation of the linear regression model.
- **`data.csv`**: The dataset used for the project (optional, if applicable).
- **`README.md`**: Documentation file explaining the project.

## Methodology
1. **Data Exploration**:
   - Analyzed the dataset to understand the structure and statistical properties.
   - Visualized the relationships between the features and the target variable.

2. **Data Preprocessing**:
   - Checked for missing values and handled them (if any).
   - Split the dataset into training and testing sets.

3. **Model Training**:
   - Implemented linear regression using the `scikit-learn` library.
   - Trained the model on the training dataset.

4. **Evaluation**:
   - Assessed model performance using metrics such as Mean Squared Error (MSE) and R² Score.
   - Visualized predictions versus actual sales values.

## Results
- **Key Insights**:
  - TV advertising had the strongest influence on sales.
  - Radio advertising also contributed significantly, while newspaper advertising had a relatively smaller impact.
- **Model Performance**:
  - Achieved an R² Score of approximately 0.9, indicating good predictive accuracy.

## Installation and Usage
### Prerequisites
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/vyuhita_24/sales-prediction-linear-regression.git
   cd sales-prediction-linear-regression
