Name: Rishav Chandra Acharya
VUNetID: acharyrc
email: rishav.c.acharya@vanderbilt.edu


- What is the dataset you chose? (include a link to the dataset)
The dataset chosen is related to California housing prices. It contains columns like longitude, latitude, housing_median_age, total_rooms, total_bedrooms, population, households,
median_income, and median_house_value.
Link to Dataset: https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/california_housing_test.csv
  
- What is the focus question you are trying to answer with this dataset? Include whether this is a classification, clustring, or other type of problem.
The focus question is: Can we predict the median house value based on the other variables, such as median income, population, and housing features?
This is a regression problem, where the target is to predict continuous house price based on other factors.

- What is your plan for cleaning this dataset? (you don't have to go into too much detail, just a general idea of what you are going to do)
  The data will be cleaned by:
  Deleting the duplicated rows
  Filling the empty values with the mean value of the columns
  Normalizing Median Income using Z-score to adjust its scale, the scale is unknown
  Removing Outliers (case: if Median Income is more than 3 standard deviations from the mean).
  
- Any extra information you'd like to include
This project will involve using machine learning algorithms like linear regression and RandomForest Regressor algorithm to predict house values. Feature selection and normalization
techniques will be applied to improve the model's accuracy.
