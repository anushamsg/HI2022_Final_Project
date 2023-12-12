# HI2022_Final_Project 
# Breast Cancer Diagnosis Prediction 
## Overview
This project focuses on predicting breast cancer diagnosis using machine learning models. The dataset used in this project contains various features related to breast cancer tumours, the data is taken from  digitalized image of breast tumour masses by fine needle aspiration and different models are trained to predict the diagnosis classifying it as benign and malignant.
# Project Structure  `data.csv`: Dataset containing information about breast cancer tumors.
# The dataset is first mounted on google drive and the file is read 
# Importing panda, numpy, matplotlib, seaborn and scipy libraries 
This code undergoes data exploration, preprocessing and model exploration.
The initial steps involve loading the dataset, exploring its structure, and performing data cleaning tasks such as removing unnecessary columns and handling missing values.
Data preprocessing is done and categorical variable handling and categorizing the dataset into training and testing sets. The variable attributes are arranged in the same values and other non used variables are eliminated.
We have performed data visualization and visualized the data in pie chart, pair plot which involves histograms and scatter plots and bar graph. We have noticed trhe distribution of diagnosis of breast cancer in the pie chart. The scatter plot here describes the diagnosis of cancer based on the variables choosen. The bar graph is also done to notice the visualization of the cancer.
We have also created a box plot and found that the dataset has outliers.
Identify and choose the variables based on their relevance to the outcome you're predicting (y value). First, we convert all data into numeric values through data encoding techniques and ensuring compatability with various machine learning models.This crucial process involves bringing all variables to a similar scale, preventing any single variable from dominating the learning process due to differences in scale. After preprocessing and normalization of data we split and train the data using k fold and access the models performance. By repeating this process with different data subsets evaluates how our model generalizes new data.
Here we have done data normalization and found some outliers and after data cleaning process we have removed the outliers. Before removing outliers and preprocessing of data we observed that the decision tree accuracy was higher when compared to naive bayes.
# from sklearn. import DecisionTreeClassifier and GaussianNB
In this step, we created, train, and test two predictive models using Decision Tree and Naïve Bayes algorithms. The evaluation metrics included Accuracy, Precision, and Recall for every target class. We built a decision tree to predict accuracy and complex relationship between data. We then used naive base model to find out the efficiency.
and overall correctness of the model. The ratio of correctly predicted positive observations to the total predicted positives, highlighting the model's precision for each class recall measures the model's ability to identify all relevant instances.
# Accuracy Comparision: Decision tree and Naive Bayes have same accuracy for the given dataset.
