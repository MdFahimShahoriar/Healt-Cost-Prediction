# HealthCost-linear_regression-Decision_tree-
     most people are a non smokers &amp; obese     feature sex, region has an almost balanced amount     person who smoke &amp; have a higher BMI, has higher medical charges     older people who smoke have more expensive charges     an obese person who smokes have higher charges
##################
*
*
*
*
*
*
##################
# Medical-Insurance-Cost-Prediction
Data source : https://www.kaggle.com/mirichoi0218/insurance

## **Project Overview** 
• Seek insight from the dataset with Exploratory Data Analysis <br>
• Performed data processing, data engineering to prepare data before modeling <br>
• Built a model to predict Insurance Cost based on the features <br>

## **Exploratory Data Analysis**

• Feature sex, region has an almost balanced amount, meanwhile most people are non smoker & obese <br>
![image](https://user-images.githubusercontent.com/80570935/130601931-826570ec-df1d-4b85-918f-00eb740ed212.png)

• A person who smoke and have BMI above 30 tends to have a higher medical cost <br>
![image](https://user-images.githubusercontent.com/80570935/130602334-b62a7f7e-e1c8-45eb-be7d-ff752853d158.png)

• Older people who smoke have more expensive charges <br>
![image](https://user-images.githubusercontent.com/80570935/130602565-2cb73fa9-769b-4822-880e-c009d2fbef39.png)

• People who smoke and obese have the highest average charges compared to others <br>
![image](https://user-images.githubusercontent.com/80570935/130602770-c008fb2b-2041-440e-b92e-373e7cbed2ce.png)

## **Data Processing**
• Check missing value - there are none <br>
• Check duplicate value - there are 1 duplicate, will be remove <br>
• Feature engineering - make a new column `weight_status` based on BMI score <br>
• Feature transformation <br>
 Encoding `sex`, `region`, & `weight_status` <br>
 Ordinal encoding `smoker` <br>
• Modeling <br>
 Separating target & features <br>
 Splitting train & test data <br>
 Modeling using Linear Regression, Random Forest, Decision Tree, Ridge, & Lasso algorithm <br>
 Find the best algorithm <br>
 Tuning Hyperparameter <br>
 
 ## **Model Evaluation**
| Score | LinearRegression | DecisionTree |
| ----------- | ----------- | ----------- |
| MAE | 4305.20 | 2798.83 |
| RMSE | 6209.88 | 6067.50 |
| R2 | 0.77 | 0.78 |
| Train Accuracy | 0.74 | 1.0 |
| Test Accuracy | 0.77 | 0.78 | 
 
 ## **Conclusion**
Based on the predictive modeling, Linear Regression algorithm has the best score compared to the others, with MAE Score 4305.20, RMSE Score 6209.88, & R2 Score 0.77. Linear Regression algorithm is fit based on the train & test accuracy.
 
