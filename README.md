# Diabetes-Prediction
## Table of content
1. General Info
2. Data EDA
3. Data preprocessing
4. Data Modeling
5. Data Interpretation

# 1.General Info
Created a simple machine learning project which is used to predict whether a women has diabetes or not, The nodel was trained and validated  using PIMA Indian Diabetes Dataset. The project was created using OSEMN(Obtaing Scrubbing Exploring Modeling Interpretation) pipeline.

# 2. Data EDA
Performed Basic EDA and statistical analysis to get a better understanding of the minimum & maximum values,missing values, mean & standard deviation value and outlier values of features used in the dataset. Used data visualisations such as histogram, scatter plot and heatmap to get a better understanding of the features and the correlation amongst the features.

# 3. Data preprocessing
Used Imputation to handle missing values. Standard Scaler method was used to standardise and scale the values of all the features to same level. Finally, the data was split using train test split method for training and validating the ml models of different algorithms.

# 4. Data Modeling 
The preprocessed dataset was used to train and validate the following machine learning algorithm KNN classification, Decision Tree classifier, Random Forest classifier and logistic regression.

# 5. Data Interpretation
Since, the KNN algorithm had the best accuracy. The results for the KNN model were visualized to find the best K value. Used confusion matrix and classification report to find the precision, recall and f-1 score of the  the model. Finally, gird search method was used for hyperparameter tuning of KNN model.



Note - The repository folder can be downloaded and directly run using Jupyter Notebook.
