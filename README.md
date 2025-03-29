# Iris Flower Classification Project

## Overview
This project involves building a model to classify the species of Iris flowers based on their features. The dataset used here is Iris dataset from Kaggle, which includes measurements for three species of Iris flowers: *Iris-setosa*, *Iris-versicolor*, and *Iris-virginica*, with keen interest in *Iris-setosa* and *Iris-versicolor*. The primary goal is to predict the species using attributes such as sepal length, sepal width, petal length, and petal width.

## Dataset
The Iris dataset contains the following columns:

- **sepal_length**: The length of the sepal in centimeters.
- **sepal_width**: The width of the sepal in centimeters.
- **petal_length**: The length of the petal in centimeters.
- **petal_width**: The width of the petal in centimeters.
- **species**: The species of the Iris flower (*Iris-setosa*, *Iris-versicolor*, *Iris-virginica*).

## Installation and Setup
1. Clone the repository or download the project files.
2. Install the required Python libraries using the following command:
   ```bash
   pip install -r requirements.txt
3. Launch notebook
    ```bash
    jupyter notebook

## Steps
1. Data Exploration: Load the dataset, examine its structure.
2. Data Preprocessing: 
    - Exempt *Iris-virginica* from dataset.
    - Map Setosa and Versicolor species to 0 and 1 respectively.
3. Model Building: Split the dataset into training and testing sets.
4. Training the model (using Logistic Regression).
    - I used Logistic Regression because it is a commonly used algorithm for solving classification problems. In this project, the task is to classify the Iris flower into one of two species (*Iris-setosa* or *Iris-versicolor*)
5. Evaluation: Evaluate the model's performance using metrics such as accuracy, precision, recall, and F1-score.
6. Visualization: Use plots (e.g., pairplots, confusion matrix) to visualize the data and results.

## FIndings
Based on the plot, Petal length and petal width are the most significant features for distinguishing species.

## Usage
To classify a new Iris flower, provide its measurements as input to the trained model. Example:
    ```bash
    model.predict([[5.1, 3.5, 1.4, 0.2]])  #Outputs: 'Iris-setosa'

## Main Dependencies
    - Pandas
    - Matplotlib
    - Seaborn
    - Scikit-learn
See requirements.txt for more details