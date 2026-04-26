# -Insurance-Premium-Prediction-Linear-Regression-
This project builds a machine learning model to predict insurance premiums based on client characteristics such as age, BMI, smoking status, and region. The goal is to understand key factors influencing insurance costs and provide accurate premium estimates for new clients.
Dataset

The dataset contains 1,338 records with the following features:

Age
Sex
BMI (Body Mass Index)
Number of children
Smoking status
Region
Insurance charges (target variable)
🔍 Exploratory Data Analysis (EDA)
The dataset is well-balanced across gender and regions
Insurance charges are right-skewed, indicating a few high-cost outliers
Smoking status has a significant impact on charges
Smokers pay substantially higher premiums than non-smokers
Age and BMI show moderate correlation with insurance costs
⚙️ Data Preprocessing
Converted categorical variables into numerical format using one-hot encoding
Split data into training and testing sets
Applied feature scaling using StandardScaler
🤖 Model Building

Three models were implemented and compared:

Linear Regression
Ridge Regression
Lasso Regression
📈 Model Performance
Linear Regression R² Score: ~0.78
Mean Squared Error (MSE): ~33.6M
Ridge and Lasso models produced similar performance, indicating model stability
🔮 Prediction Example

The model can estimate insurance premiums for new clients.
Example:

Input: Age = 30, BMI = 26, Smoker = Yes
Predicted Premium: ~$27,365
Conclusion

This project demonstrates how machine learning can be used to predict insurance costs and uncover key cost drivers, providing valuable insights for both businesses and customers.
