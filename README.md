Regression-Modeling-Experiment

This repository contains a series of experiments to explore and compare different regression models, including a basic linear regression model and flexible models with polynomial features. The focus is on evaluating how model flexibility affects prediction accuracy, using Mean Squared Error (MSE) as the performance metric.

Overview

The code generates synthetic data with five input features and a response variable that is a linear combination of these features, with some added noise. It then applies three regression models:
	1.	Linear Model: Basic linear regression using the least squares method.
	2.	Flexible Model: A model that adds polynomial features (e.g., x_1^2) to introduce non-linearity.
	3.	More Flexible Model: An even more flexible model, adding higher-order polynomial features (e.g., x_1^2, x_2^2).

The models are evaluated using training and test data, and the Mean Squared Error (MSE) is calculated for each model. A plot is generated to visualize the impact of increasing flexibility on model performance.

Features

	•	Data Generation: The dataset consists of 1,000 observations with 5 input features, generated using a mix of uniform, normal, and exponential distributions.
	•	Least Squares Regression: Implements the least squares method to compute regression coefficients.
	•	Model Flexibility: Three levels of model flexibility are compared by adding polynomial terms to the feature set.
	•	MSE Evaluation: Calculates MSE for both the training and test datasets for each model to evaluate their performance.
	•	Visualization: A plot comparing test MSE values for each model, showing the relationship between model flexibility and prediction accuracy.

Requirements

	•	Python 3.x
	•	NumPy
	•	Matplotlib

Installation

	1.	Clone this repository:
       git clone https://github.com/your-username/Regression-Modeling-Experiment.git
 	2.	Install the necessary dependencies:
      pip install numpy matplotlib

 Usage

	1.	Navigate to the directory containing the script.
	2.	Run the Python script to generate the dataset, train the models, and plot the results:
      python regression_modeling.py

  Results

The script will output the Mean Squared Error (MSE) for the training and test sets for each model, and it will display a plot comparing the test MSE values of the three models.

License

This project is licensed under the MIT License.
   