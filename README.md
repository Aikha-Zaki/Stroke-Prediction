# stroke-prediction
The analysis both in R and Pyhton were done in Google colab

# Introduction

Stroke is a medical disorder that happens due to arteries rupture or blockage in the brain causing damage to the brain. It can cause serious long-term disability and in the worst cases, it might lead to death. The probable risk factors for stroke include hypertension, diabetes, smoking, age, sex, obesity, environment, and others.

# Problem Statement 

The objective of this project is to find the likeliness of a stroke happening in a person. Ideally, this project might provide initial insight into the early detection of stroke and obtain early treatment. Different machine learning models have been used to predict the possibility of a stroke to occur. The algorithm used in this project are logistic regression, KNN, and decision tree to train three different models for reliable prediction. This dataset is obtained from Kaggle and the analysis is carried out using R and Phyton language using Google Colab Platform. 

# Dataset

There were 4981 rows and 11 columns in the dataset. The value of the output column stroke is 1 or 0 which indicates the stroke risk was detected and vice versa, respectively.  4733 rows is identified to be 0 and 248 have the value of 1. 

# Steps Implemented

1) DATA PREPROCESSING & OUTLIERS ANALYSIS

Firstly, missing data is checked and filled in if any are detected. The outliers then are detected using boxplot and histogram analysis. In this analysis, the outliers were not omitted since they represent natural variations in the population. Removing them will affect the analysis. Afterward, the non-numeric columns were checked for any inconsistencies. Based on our analysis, one of the columns (smoking_status) has data labeled as unknown. Since the count is high, they were replaced with the most frequent category which is "never smoked". All the categorical variables (strings) have also been converted into factors for the computer to able to comprehend them since they are trained on numbers.

2) DATA VISUALIZATION

Pie charts were used in this analysis to depict the recurrence dispersion of the categorical variables while histogram graphs were used for numerical variables.

3) MACHINE LEARNING

According to the analysis, the classification accuracy of all models are ~ 95 percent. However, since the sample size of patients with stroke is significantly smaller than the ones without stroke, the conclusion derived here is not applicable to the general population. The analysis can be further improved by using a larger dataset and other machine learning models.

 - Logical Regression
  - Decision Tree
  - KNN
  
4) Shiny is the online tool allowing to upload your charts, maps and characterize and visualize them. Several interactive graphs are available with export options and more. The tool was created using R and Shiny. Below is the example of histogram that have been created using this tool.

![image](https://user-images.githubusercontent.com/116784311/213180980-697167f3-eedf-4ac0-b60f-55cdc8ffeb21.png)

