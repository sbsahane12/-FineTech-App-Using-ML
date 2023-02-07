# [Project  6: FineTech App Using ML](https://github.com/sbsahane12/-FineTech-App-Using-ML.git) 
## Problem Statement
- Follow the “Directing Customers to Subscription Through Financial App Behavior Analysis Machine Learning End to End Project” step by step to get 4 Bonus.
- We are finding how much time the customer takes to get enrolled in the premium feature app after registration. For that subtract ‘fineTech_appData.first_open’ from ‘fineTech_appData.enrolled_date’ and set data type as timedelta64 in hours.
## Problem Approach
- 1)We saw the heatmap correlation matrix but this was not showing correlation clearly but you can easily understand which feature is how much correlated with ‘enrolled’ feature using the above barplot.     
- 2)The ‘numscreens’ and ‘minigame’ is strongly positively correlated with ‘enrolled’ feature than other feature. 
- 3)The ‘hour’, ‘age’ and ‘used_premium_feature’ are strongly negatively correlated with the ‘enrolled’ feature.
## Steps :
- Data Inspection – Missing Values if any, EDA
- Outlier Analysis
- Data Pre-processing
- Finding Optimal number of Clusters
- Modelling
- KMeans Clustering
- Hierarchical Clustering – Single and Complete Linkages
- Listing down top 5 countries in need
## Install
This project requires Python 3.6 and the following libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)
- 
## Machine Learning Model Building
- The target variable is categorical type 0 and 1, so we have to use supervised classification algorithms.To build the best model, we have to train and test the dataset with multiple Machine Learning algorithms then we can find the best ML model. So let’s try.First, we import the required packages.
