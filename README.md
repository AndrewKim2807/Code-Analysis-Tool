# Decision Tree Classifier for Predicting Labels

This Python program uses a Decision Tree Clasifier to predict labels for a given test dataset.

## Table of Contents
- Introduction
- Technologies Used
- Setup
- Usage
- License


## Introduction
For the purpose of predicting the labels of a given test dataset, the program employs a trained Decision Tree Classifer modedl. The test dataset has ben preprocessed to eliminated duplicates and null values, and the feature and labels have been divided into 2 groups. X test and y test.

The trained model is loaded and used to make predictions on the X test. The accuracy of the predictions is assessed using the sklearn.metrics library's accuracy score function.

## Technologies Used
- Python 3
- pandas Library for data manipulation
- scikit-learn library for machine learning
- scipy library for reading arff files
- io library for reading data from bytes

## Setup
How to use this program:
1. Clone this repository to your local machine or run the program in **Google Colaboratory**.
2. Upload your dataset to Google Colab through the upload button.
3. Run the program by executing each cell in order. The program will output the accuracy of the predictions.

## Usage
Using a Decision Tree Classifier, The program may be used to forecase class labels for any dataset. Use the upload button to submit your dataset to Google Colab in order to use the program. Then, execute each cell in turn to run the program. The application will display the prediction accuracy.

## License
This program is licensed under the MIT Licecnse. See the LICENSE file for details.
