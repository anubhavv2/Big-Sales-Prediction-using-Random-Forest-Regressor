# Big Sales Prediction Using Random Forest Regressor
##  Project Overview
This project involves predicting sales using a Random Forest Regressor. The dataset used is the "Big Sales Data," and the goal is to predict the Item_Outlet_Sales based on various features like item 
characteristics and outlet information.

##  Dataset
The dataset consists of 14204 entries and 12 columns.

##  Data Preprocessing
Loading Data: The dataset is loaded into a Pandas DataFrame.

Handling Missing Values: Missing values in Item_Weight are filled with the mean weight of the corresponding Item_Type.

Encoding Categorical Variables: Categorical variables are converted to numerical values using label encoding.

Standardizing Features: Continuous features (Item_Weight, Item_Visibility, Item_MRP, Outlet_Establishment_Year) are standardized to have a mean of 0 and a standard deviation of 1.

##  Model Training
Train-Test Split: The data is split into training and testing sets with a 90-10 ratio.

Random Forest Regressor: A Random Forest Regressor model is trained on the training set.

##  What is Random Forest Regressor?
Random Forest Regressor is an ensemble learning method for regression tasks. It operates by constructing multiple decision trees during training and outputting the average of the 
predictions of the individual trees. This helps to improve the predictive accuracy and control over-fitting.

##   Model Evaluation
Mean Squared Error (MSE): Measures the average squared difference between the actual and predicted values.

Mean Absolute Error (MAE): Measures the average absolute difference between the actual and predicted values.

R² Score: Indicates how well the model predicts the target variable, with 1 being a perfect prediction.


##   Visualization
A scatter plot of actual vs. predicted sales values is created to visualize the model's performance.
