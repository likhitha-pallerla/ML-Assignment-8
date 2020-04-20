# ML-Assignment-8

IBM-HR-Analytics-Employee-Attrition-Performance dataset..

Question-->

Objective: Build models using all classification algorithms other than neural networks and and compare the accuracy using methods discussed with them

Uncover the factors that lead to employee attrition and explore important questions such as ‘show me a breakdown of distance from home by job role and attrition’ or ‘compare average monthly income by education and attrition’ (It's up to you to explore and find patterns in the dataset by asking questions of your choice). Finally, predict the “Attrition” from this data set. 

Assignment Guidelines: 
1. Do basic analysis and Visualization of all the columns and select the columns which you feel are relevant for solving the problem statement. (Don’t forget to preprocess your data) 
2. Explore different scoring metrics (like F1 score, accuracy, precision, etc.) and select the most relevant. 
3. Experiment with different classification algorithms and Don’t forget to perform hyperparameter tuning on these models 
4. Make sure to provide import features for at least one of the models 5. Finally in conclusion section make sure to compare all your models  

My Solution-->

I have first performed Exploratory Data Analysis on the data using various libraries like pandas,seaborn,matplotlib etc..  

Then I have also used feature selection techniques like RFE (a wrapper method )to select the features. The data is then oversampled using the SMOTE technique in order to deal with the imbalanced classes. Also the data is then scaled for better performance.  

Lastly I have trained many ML models from the scikit-learn library for predictive modelling and compared the performance using Precision, Recall and other metrics .
