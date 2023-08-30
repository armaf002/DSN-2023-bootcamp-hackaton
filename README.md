# Executive Report: Predictive Model for House Price Estimation

## Introduction
Wazobia Real Estate Limited is a leading real estate company based in Nigeria, renowned for its extensive property portfolio and commitment to providing accurate and competitive pricing for houses. However, accurately predicting house prices in the dynamic real estate market poses challenges. To address this, Wazobia Real Estate Limited partnered with Microsoft and Data Scientists Network (DSN) to organize a hackathon on the Zindi.africa platform. The primary objective was to develop a robust predictive model capable of accurately estimating house prices in Nigeria.

## Objective
The objective of the hackathon was to create a powerful and accurate predictive model capable of estimating house prices in Nigeria. The successful development of this model aimed to empower Wazobia Real Estate Limited with an effective tool for making informed pricing decisions, enhancing market competitiveness, and delivering enhanced value to its customers. Additionally, the hackathon sought to foster the growth and experience of young data scientists, providing them with an opportunity to showcase their skills and expertise.

## Hackathon Overview
The hackathon brought together data scientists, researchers, and experts from various fields to collectively tackle the complex challenge of accurate house price prediction. Leveraging the provided dataset, participants were tasked with analyzing a myriad of factors influencing house prices. Through rigorous data exploration, feature engineering, and machine learning techniques, participants aimed to develop models capable of generating reliable price predictions.

## Methodology and Result
### Data Exploration and Preprocessing
A thorough data exploration was conducted on the provided datasets: Housing_dataset_train.csv, Housing_dataset_test.csv, and Sample_submission.csv. The training set contained approximately 14,000 entries, while the test set comprised around 6,000 entries. The dataset included features such as location, title, number of bedrooms, bathrooms, parking spaces, and the target variable—house prices in Million Naira.

Data preprocessing involved handling missing values, outliers, and skewed data. Missing values in the 'loc' and 'title' columns were dropped, while other numeric columns were filled with suitable imputation techniques. Outliers in the target variable (price) were addressed using 5th and 95th percentiles. Additional features such as 'total_rooms,' 'bedroom_bathroom_ratio,' 'bathroom_type,' 'bedroom_group,' and 'region' were engineered to provide valuable insights for the predictive model.

### Model Deployment and Evaluation
Various regression models were implemented to predict house prices, including Linear Regression, RandomForestRegressor, Gradient Boosting, AdaBoost, Support Vector Regression, K-Nearest Neighbors, Decision Tree, CatBoost, XGBoost, LightGBM, Lasso, Ridge, and ElasticNet. Extensive hyperparameter tuning using KFold cross-validation was conducted to identify the optimal configurations for the top performing models—CatBoost, LightGBM, and Gradient Boosting. These models were further evaluated in terms of Root Mean Squared Error (RMSE), with the Gradient Boosting Regressor emerging as the best performer, achieving an RMSE of approximately 302,345.52. This model was chosen for its robustness and accurate predictions.

### Feature Importance Analysis
The analysis of feature importance provided critical insights into the factors influencing house prices. Key features such as 'title,' 'bedroom,' 'region,' and 'location' were found to have a significant impact on house prices. Additionally, engineered features like 'total_rooms' and 'bedroom_group' also played essential roles in the predictive model.

## Conclusion
In conclusion, the hackathon organized by Wazobia Real Estate Limited, Microsoft, and Data Scientists Network has been a remarkable endeavor in developing a powerful predictive model for house price estimation. The chosen Gradient Boosting Regressor model demonstrated an exceptional accuracy and robustness, making it a valuable asset for Wazobia Real Estate Limited to make data-driven pricing decisions and enhance their competitive edge in the Nigerian real estate market.

