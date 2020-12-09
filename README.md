# Predicting-wine-quality

# Table of Content :
1. Introduction 2. Objectives 3. Data Description 4. Data Analysis 5. Methodology 6. Data Preprocessing 7. Machine Learning Algorithm  8. Application

1.INTRODUCTION The aim of this project is to predict the quality of wine on a scale of 0–10 given a set of features as inputs.For this project, I used Kaggle’s Red Wine Quality dataset to build various classification models to predict whether a particular red wine is “good quality” or not. Each wine in this dataset is given a “quality” score between 0 and 10. For the purpose of this project, I converted the output to a binary output where each wine is either good quality “RatingQuality”(a score of 7 or higher) or not (a score below 7). Dataset/Source: Kaggle https://www.kaggle.com/uciml/red-wine-qua lity-cortez-et-al-2009 Structured/Unstructured data: Structured Data in CSV format Software Requirement of Project : Python and jupyter notebook 

2.OBJECTIVES 
 
• Our main objective is to predict the wine quality using machine learning through Python programming language. • A large dataset is considered and wine quality is modelled to analyse the quality of wine through different parameters like fixed acidity, volatile acidity etc. 
 
• All these parameters will be analysed through Machine Learning algorithms like random forest classifier algorithm which will helps to rate the wine on scale 1 - 10 or bad - good. 
 
• Output obtained would further be checked for correctness and model will be optimized accordingly 
 
 3.DATA DESCRIPTION 
 
Input variable that determine quality of vine (based on physicochemical tests): 1 - fixed acidity     4 - residual sugar         7 - total sulphur dioxide 2 - volatile acidity    5 - chlorides          8 - density  3 - citric acid             6 - free sulphur dioxide   9 - pH                10 - sulphates         11 - alcohol Output variable : quality (score between 0 and 10) 

4.DATA ANALYSIS 
 
• The two most important features among all 11 attributes are Sulphur dioxide (both free and total) and Alcohol. • Volatile acidity contributes to acidic tastes and have negative correlation to wine quality. • The most important factor to decide the quality of wine is alcohol, higher concentration of alcohol leads to better quality of wine and lower density of wine 
 
 
 5.METHODOLOGY 
 
It gives insights of the dependency of target variables on independent variables using machine learning techniques to determine the quality of wine because it gives the best outcome for the assurance of quality of wine.  The dependent variable is “quality rating” whereas other variables i.e. alcohol, sulphur etc. are assumed to be predictors or independent variables. While hindering the effectiveness of the data model, various types of errors have occurred like over fitting, introduced from having too large of a training set and bias occur due to too small of a test set. 

6.DATA PREPROCESSING 
 
In this step we can remove unnecessary columns from the dataset as these columns won't affect accuracy that much. Since i wanted to compare the effectiveness of different classification techniques, so I needed to change the output variable to a binary output. For this project, I defined a bottle of wine as ‘good quality’ if it had a quality score of 7 or higher, and if it had a score of less than 7, it was deemed ‘bad quality’. Once I converted the output variable to a binary output, I separated my feature variables (X) and the target variable (Y) into separate dataframes. 

7.MACHINE LEARNING ALGORITHM 
 
In this project i have done some exploration on the data using matplotlib and seaborn. Then, I use different classifier models to predict the quality of the wine. Following are the classifier- 
 
1. Decision Tree Classifier 2. Random Forest Classifier 3.Logistic Regression Classifier 
 
Algorithms used for classification are: • Decision Tree - Decision Tree is a Supervised learning technique that can be used for both classification and Regression problems, but mostly it is preferred for solving Classification problems. It is a tree-structured classifier, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome. 
 
• Random Forest - Random forest is a supervised learning algorithm which is used for both classification as well as regression. But however, it is mainly used for classification problems. As we know that a forest is made up of trees and more trees means more robust forest. Similarly, random forest algorithm creates decision trees on data samples and then gets the prediction from each of them and finally selects the best solution by means of voting. It is an ensemble method which is better than a single decision tree because it reduces the over-fitting by averaging the result. 
 
• Logistic Regression - Logistic regression is a supervised learning classification algorithm used to predict the probability of a target variable. The nature of target or dependent variable is dichotomous, which means there would be only two possible classes. In simple words, the dependent variable is binary in nature having data coded as either 1 (stands for success/yes) or 0 (stands for failure/no).

7.APPLICATION 
 
• Results will be used by the wine manufacturers to improve the quality of the future wines. • Certification bodies can also use the result for quality control. • Results can be used to make wine selection guides for wine magazines. • Results can be used by consumers for wine selection 
