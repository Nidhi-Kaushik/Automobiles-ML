# Automobiles-ML

Collected data from UCI Machine Learning repositories. It is a regression problem containing 205 instances and 26 attributes with both numerical and categorical values. 

Data Source:  
link: https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data

Description: 
Most of the project is based on cleaning and preprocessing of data. Use of inbuilt functions (like describe and .isnull) to check if any null value is present in data. Conversion of datatype of attributes using .info() .As we have given many attributes; we need to check how much they are corelated to each other for better understanding of data, which can be done using heatmap. We might have lots of missing values, no need to drop all of them; we can also replace null values using aggregates like mean, median, mode, count etc. Standardising also plays main role in preprocessing of data. Use of scatter plot, box and whiskers plot has been done to analyse data more precisely. To know more about data, we used groupby function to play around with data to get useful information. At last, we applied Artificial Neural Network (ANN) to train our model and to get best accuracy.
