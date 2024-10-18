# Health Insurance Analysis

## Project Overview
This project aims to analyze a dataset containing information about health insurance charges and to build a linear regression model to predict these charges. The analysis includes data preprocessing, exploratory data analysis (EDA), and model evaluation.

## Dataset
The dataset is sourced from the [US Health Insurance Dataset](https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset) on Kaggle. It contains the following features:

- **age**: Age of the insured individual
- **sex**: Gender of the insured individual (male, female)
- **bmi**: Body Mass Index (a measure of body fat)
- **children**: Number of children/dependents covered by the insurance
- **smoker**: Indicates if the insured individual is a smoker (yes, no)
- **region**: The region of the insured individual (northeast, southeast, southwest, northwest)
- **charges**: The medical charges incurred by the insured individual (target variable)

## Features
- Data cleaning: Handles duplicate rows and encodes categorical variables.
- Exploratory Data Analysis: Visualizes the distribution of the target variable and correlations between features.
- Machine Learning: Implements a linear regression model to predict insurance charges.
- Model Evaluation: Uses metrics such as Mean Squared Error (MSE) and R-squared (R²) to assess model performance.

## Requirements
To run this project, ensure you have Python 3.x and the following libraries installed:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- kagglehub

## Installation
To install the required packages, create a `requirements.txt` file with the following content:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- kagglehub

Then, you can install the packages using pip:

```bash
pip install -r requirements.txt
```

# Visualization

The script generates the following visualizations:

	•	Distribution of Insurance Charges: A histogram showing the frequency distribution of insurance charges.
	•	Correlation Heatmap: A heatmap displaying the correlation between various features in the dataset.
	•	Actual vs Predicted Charges: A scatter plot comparing the actual insurance charges to the predicted values from the model.

# Model Performance

The model is evaluated using:

	•	Mean Squared Error (MSE): Measures the average squared difference between the actual and predicted values.
	•	R-squared (R²): Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.
