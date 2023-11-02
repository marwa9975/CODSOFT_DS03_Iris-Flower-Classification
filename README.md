
# **Iris Flower Classification**
![Iris Flower](https://upload.wikimedia.org/wikipedia/commons/5/56/Kosaciec_szczecinkowaty_Iris_setosa.jpg)   


## **Project Overview**
The Iris Flower Classification project is a supervised classification task that aims to accurately classify Iris flowers into one of three distinct species: 'setosa,' 'versicolor,' and 'virginica.' Classification is based on the flowers' sepal and petal measurements, leveraging a dataset containing these numerical features. This project explores the world of machine learning and serves as a foundation for introductory classification tasks.

## **Business Understanding**
### Problem Statement
The main objective of this project is to develop a machine learning model capable of accurately classifying Iris flowers into their respective species ('setosa,' 'versicolor,' and 'virginica') based on their sepal and petal measurements.

### Relevance
Accurate Iris flower classification is of significant interest to botanists, horticulturists, and researchers studying plant species. It is also a valuable educational tool for teaching introductory machine learning and classification concepts.

### Project Objectives
Primary Objective:  
* Train a machine learning model to classify Iris flowers into three species based on sepal and petal measurements.

Secondary Objectives:
* Explore and analyze the Iris dataset to gain insights into its characteristics.
* Preprocess the data to make it suitable for machine learning.
* Select an appropriate machine learning algorithm for classification.
* Train and evaluate the model's performance using relevant metrics.
## **Data UNderstanding** 
Data Source  
The dataset used in this project is the Iris dataset, obtained from Kaggle: [Iris Flower Dataset](https://www.kaggle.com/datasets/arshid/iris-flower-dataset)


Data Description    
The dataset includes the following columns:

* sepal_length: Sepal length in centimeters (numerical)
* sepal_width: Sepal width in centimeters (numerical)
* petal_length: Petal length in centimeters (numerical)
* petal_width: Petal width in centimeters (numerical)
* species: The target variable, indicating the Iris species (categorical - 'setosa,' 'versicolor,' 'virginica')

## **Modeling***
Models Used:  
Model 1: Logistic Regression   
Model 2: Support Vector Classifier (SVC)   
Model 3: Random Forest  
### Model Comparison
Compared the three models in terms of accuracy and performance on the test data.    
Identified Logistic Regression and SVC as top-performing   models and selected Logistic Regression for further tuning.    
Model 4: Hyperparameter Tuning of Logistic Regression Model
### Model Evaluation
Evaluated the tuned Logistic Regression model on the training and test datasets.   
Calculated accuracy, precision, recall, F1-scores, and confusion matrices.   
Demonstrated strong model performance and generalization.


## **Conclusions** 
Successfully addressed the problem of Iris species classification using machine learning models.  
The tuned Logistic Regression model exhibits exceptional performance in classifying Iris flowers into their respective species based on sepal and petal measurements.
The Iris Flower Classification project is a valuable tool for botanists, researchers, and educators interested in Iris species classification.

## Getting Started  
Prerequisites
To run this project, you need to have Python and the following libraries installed:

pandas
numpy
seaborn
matplotlib
scikit-learn
Installation
You can install the required libraries using pip:

Author
Marwa Osman
marwaosman9975@gmail.com
