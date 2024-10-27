# Car Price Prediction

This project uses machine learning to predict the price of a car based on its features.

## Dataset

The dataset used for this project is "CAR DETAILS FROM CAR DEKHO.csv". It contains information about cars, including their name, year, selling price, km driven, fuel type, seller type, transmission, and owner.

## Preprocessing

The data is preprocessed by:

1. Replacing categorical values with numerical values.
2. Separating the target variable (selling price) from the features.
3. Splitting the data into training and testing sets.
4. Scaling the features using StandardScaler.

## Model

A Linear Regression model is used to predict the car price. The model is trained on the training data and evaluated on the testing data.

## Evaluation

The model's performance is evaluated using the R2 score. The R2 score for the training data is printed to the console. The R2 score for the testing data is printed to the console along with a scatter plot comparing the actual and predicted prices.

## Usage

To use this project, simply run the code in a Google Colab notebook. The code will download the dataset, preprocess it, train the model, and evaluate its performance.

## Requirements

This project requires the following libraries:

* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn

You can install these libraries using pip:

## Conclusion

This project demonstrates how to use machine learning to predict the price of a car. The Linear Regression model achieved a good R2 score on both the training and testing data, indicating that it is a good predictor of car prices.
