# Venture Funding with Deep Learning

### Package Requirments

`pip install x` where x is the below listed packages
* pandas
* pathlib
* tensorflow
* scikit-learn

### Purpose of Use
* A model was created in order to predict whether or not organizations will be successful if given funding by Alphabet Soup. Using knowledge of machine learning and neural networks, the features in the provided dataset were used to create a binary classifier model that predicted whether an applicant will become a successful business.
* The analysis contains three parts:
  * Prepare the Data for Use on a Neural Network Model
  * Compile and Evaluate a Binary Classification Model Using a Neural Network
  * Optimize the Neural Network Model

### Files Navigation
* Resources: Directory containing all necessary csv files and models
* `venture_funding_with_deep_learning.ipynb`: Notebook containing all data analysis and predictions

### Solution
* Original Model Results:
  * Number of hidden nodes for the first hidden layer: 58 (half the total number of features)
  * Number of hidden nodes for the second hidden layer: 29
  * Accuracy Score: 73.08%
* Alternative Model 1 Results:
  * Number of hidden nodes for the first hidden layer: 232 (double the total number of features)
  * Accuracy Score: 72.89%
* Alternative Model 2 Results:
  * Number of hidden nodes for the first hidden layer: 348 (triple the total number of features)
  * Accuracy Score: 73.15%

It appears as though the results are not significant enough to make a difference in the three models. However, the second alternative model performed the best with an accuracy score of 73.15%.

