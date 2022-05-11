# Project 3: Binary Logistic Regression
Binary logistic regression on Fish.csv dataset.

## Code Breakdown
### Step 0: Define function_0 to normalize the dataset
`input_feature_norm = function_0(input_feature)`

### Step 1: Define function_1 to predict the model output
`predicted_output_binary = function_1(input_feature, weight)`

### Step 2: Define function_2 to calculating model accuracy
`accuracy = function_2(predicted_output_binary, output_binary)`

### Step 3: Define function_3 to Estimating and Printing Logistic Regression Coefficients
`weight, train_accuracy_history, test_accuracy_history = `
    `function_3(train_feature, train_output, test_feature, test_output, weight0, learning_rate, tolerance)`

### Step 4: Import fish data from Fish.csv
1. Importing fish data from Fish.csv using panda.read_csv function;
2. Converting Panda data to Numpy data;
3. Random spliting the data into 80% training and 20% test data (train_feature, test_feature, train_output, test_output);
4. Saving input features and output weigth separately;

### Step 5: Use function_1 to train ‘One vs All’ binary classification models
The data contains Seven species of Fish. Use the defined functions to learn Seven ‘One vs All’ binary classification models. Show test/train accuracy for each model. 
Use followings as input_features

A. Length1 (Vertical Length in cm)
B. Length2 (Diagonal Length in cm)
C. Length3 (Cross Length in cm)
D. Height (cm)
E. Width (Diagonal width in cm)
F. Weight

## Main files to check
The main file to check is the Jupyter notebook where:
- The functions are defined;
- The data is given;
- Then, the functions are called;
- The results are displayed and saved.

## Setup
Install [Miniconda](https://conda.io/miniconda).
Then, run the jupyter notebook in the "code" folder.

## Acknowledgment and References
This project has been developed based on the assignment provided by Dr. Abdul Bais, P.Eng. (abdul.bais@uregina.ca), my instructor for the course “ENEL-865/ENSE 865: Applied Machine Learning”.

This assignment is based on the first assignment of Machine Learning Regression course (from Coursera). 

- Dr. Abdul Bais, P.Eng. (abdul.bais@uregina.ca) page: 
https://www.uregina.ca/engineering/faculty-staff/faculty/bais-abdul.html

## Dataset
Download the Fish Market Dataset from Kaggle (https://www.kaggle.com/aungpyaeap/fish-market) to estimate weight of fish. Random split data into 80% training and 20% test data.

## My contribution
All scripts are written by my self.
______________
Marzieh Zamani