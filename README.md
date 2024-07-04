# Data_Science_Project_Gender_Detection_by_Tooth_Size

This is a classicfication supervised learning data science project where we have build a model which predicts the gender on the basis of the features of the tooth size, this model can be very usefull for forensic studies as it will help them in identifying the gender of the specimen which will help them in further exploration of their findings.

To make this model we have used classification supervised learning models as our dependent/labeled feature gender is an object data type, to build the model we have followed the following steps:

<ol>
  <li>Importing necessary libraries like numpy, pandas, matplotlib, seaborn, then reading the data set and saving it into a  variable. Further, checking dataset and doing basic exploration like - checking for null values, knowing all the features in data set, checking for features that can be imputed/droped, checking for outliers, knowing the features in a better way with each features description.</li>
  <li>After, doing the basic exploration we have droped the categorical data which is not adding usefullness for our model building, replacing the outliers with median values in each of the numerical features of our data set to make our data more uniformally distributed.</li>
  <li>Further, we have done the basic EDA by building different visualization like - histogram, coutplot, boxplot, heatmap for coorelations.</li>
  <li>Then, we have process our data further and break it out to x and y variables, where x is independent and y is dependent feature, then we have split our x and y variables into train and split data with the help of sklearn library, after that we have made our x_train and x_test data normalized with the help of sklearn standardization</li>
  <li>Now, as our data is completely processed and ready, we have test our data with different machine learning algorithms like - logistic regression, decission tree, random forest, xgboost, gradientboost, to furether evaluate the result we have used the classification performance metrics sunch as - accuracy, precission, recall and f1 test.</li>
  <li>To further validate our finding we have done the visualizaation for the best algorithm which has performed best among the all by using the confusion metrix, roc and auc curve. </li>
</ol>

**** Do check the supported documents which are attached to this repositry to have indepth knowledge of the project ******
