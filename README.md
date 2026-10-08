# Automated_Analysis_Assignment
Link to Notebook: [(https://colab.research.google.com/drive/1Jgj3ppOVspvRk_UkNuDT1PQOKovLkzaG?usp=sharing)]

Purpose
To practice automating the different steps of the analysis pipelines in order to create more efficient, and more readable code and analysis notebooks. This practice uses the Pima Indians Diabetes Dataset from the NIH National Institute of Diabetes and Digestive and Kidney Diseases, which has the binary outcome of 0, No diabetes, and 1, Diabetes. 

Required packages and libraries
Libraries and versions (when applicable):

   - pandas
   - google.colab import files
   - io
   - pathlib import Path
   - numpy
   - seaborn
   - matplotlib.pyplot
   - phik, import resources, report, plot_correlation_matrix phik_matrix
   - os
   - sys
   - subprocess
   - math
   - scipy.stats, import ttest_1samp, ttest_ind, and chi2_contingency
   - statsmodels.api
   - statsmodels.formula.api import ols
   - sklearn.model_selection import train_test_split, StratifiedKFold, cross_val_predict, GridSearchCV, StraifiedKFold
   - sklearn.metrics import confusion_matrix, accuracy_score, recall_score, precision_score, f1_score, roc_auc_score, roc_curve, classification_report
   - sklearn.pipeline import Pipeline
   - sklearn.impute import SimpleImputer
   - sklearn.preprocessing import StandardScaler
   - sklearn.linear_model import LogisticRegression
   - sklearn.tree import DecisionTreeClassifier, plot_tree
   - textwrap
   - matplotlib.ticker import PercentFormatter

Setup and Installation
Load the specified libraries and packages and upload dataset by following the instructions. A message will print when completed successfully.

Instructions for executing notebook
Go through each chunk of code in order (or select 'Run all' at the beginning.

Brief description of analysis
Beginning with the initial data review and validation, Identify missing values. 
Then complete the exploratory data analysis, including producing correlation tables for all the variables and general distribution visuals of the variables. 
Complete the Inferential Statistics to determine if there is evidence that the mean of certain variables, like Glucose, is the same for each Diabetes Outcome group. 
Then complete the code for the supervised machine learning models, including both Logistic Regression and Decision Tree models. 
Evaluate these two models by Accuracy, Recall, Precision, F1, and ROC-AUC. 


