# Diabetes-Project

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.  

Attribute Information:     
Number of times pregnant    
Plasma glucose concentration a 2 hours in an oral glucose tolerance test  
Diastolic blood pressure (mm Hg)  
Triceps skin fold thickness (mm)  
Hour serum insulin (mu U/ml)  
Body mass index (weight in kg/(height in m)^2)  
Diabetes pedigree function  
Age (years)  
Class variable (0 or 1)  

### Overview of the project steps 

1.Prepare Problem  
a) Load libraries needed for this problem  
b) Load dataset from Kaggle (Pima Indians Diabetes Database)  
2.Summarize Data  
a) Descriptive statistics: summarizing the distribution of each attribute  
b) Data visualizations: drawing histograms, density, skewness and kurtosis of each attribute, to detect possible exponential and bimodal distributions, also the outliers - checking the target distribution (specific to classification problems) - visualizing interactions between attribute  
4. Evaluate Algorithms  
a) Split-out validation dataset : using 80% of the dataset for modeling and hold back 20% for test  
b) Data Transforms & Spot-Check Algorithms: standardizing data and evaluating some alogorithms to get an idea on the performance of each algorithm, using the 10-fold cross-validation { Logistic Regression (LR), Linear Discriminant Analysis (LDA), k-Nearest Neighbors (KNN), Classiﬁcation and Regression Trees (CART), Gaussian Naive Bayes (NB), Support Vector Machines (SVM) }.  
c) Compare Algorithms  
d) Outliers investigation  
e) Feature selection : estimating the importance of features using Bagged decision trees like Random Forest and Extra Trees  
5. Improve Accuracy  
a) Algorithm Tuning  
b) Ensembles  
6. Finalize Model : predictions on test dataset
