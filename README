# Predicting Beauty Product Customer Reviews

## Overview
The primary aim of this project is to develop a predictive model that estimates customer review ratings for beauty and cosmetic products based on product characteristics, while identifying the most influential variables. More specifically, we seek to determine which product attributes such as price, ingredients, cruelty-free status, packaging type, and country of origin are most strongly associated with higher customer satisfaction ratings.

This project addresses the uncertainty that companies face when launching new products. Companies often rely on intuition and smaller groups of testers, which introduces risk when a product is released to a larger market. Data-driven insights may help mitigate this risk by identifying important characteristics that define higher rated products that have already been released on scale. With a successful model, we aim to predict product success prior to a product being released to the market.

## Research Problem
Can we predict customer review ratings of beauty products using product attributes, and which features are most strongly associated with higher customer satisfaction?

## Dataset
We are using a dataset from Kaggle that contains information about companies selling beauty products globally in the cosmetic industry. The dataset includes both categorical and numerical variables and contains approximately 15,000 observations.

The dataset includes features such as:
- Product price
- Main ingredient
- Cruelty-free status
- Packaging type
- Country of origin
- Number of reviews
- Customer review rating (target variable)

Preliminary data exploration showed:
- No missing values across all variables
- An average product rating of approximately 3.00
- Ratings range from 1 to 5
- No strong linear relationship between price and rating based on initial visualizations

## Methodology
We are using a combination of statistical and machine learning models to predict customer ratings. The methods include:
- Linear Regression
- Random Forest
- Gradient Boosting

The dataset requires preprocessing due to the mix of categorical and numerical variables. This includes:
- One-hot encoding for categorical variables
- Scaling for numerical variables
- Train-test split (80/20)
- Cross-validation for model evaluation

Initial data exploration includes summary statistics, correlation analysis, and visualizations to better understand relationships between variables.

## Preliminary Results
Initial model performance suggests that predicting customer ratings is challenging with the current feature set.

Model performance results:
- Linear Regression  
  - RMSE: 1.1774  
  - R²: -0.0096  

- Random Forest  
  - RMSE: 1.1874  
  - R²: -0.0268  

- Gradient Boosting  
  - RMSE: 1.1781  
  - R²: -0.0107  

Cross-validation results showed similarly low predictive performance across all models, with R² values near zero or slightly negative.

Feature importance analysis from the Random Forest model identified:
- Price
- Number of reviews

as the most influential predictors, although their overall impact is relatively weak.

These results suggest:
- There may not be strong predictive signals in the current dataset
- Customer satisfaction may be influenced by variables not included in the dataset
- Additional feature engineering or alternative modeling approaches may be necessary

## Possible Outcomes
Our success in this project will be evaluated by the predictive accuracy achieved with our models. We will compare linear regression, random forest, and gradient boosting to determine which performs best.

Model performance will be evaluated using:
- Root Mean Squared Error (RMSE)
- R-squared (R²)

Possible outcomes include identifying key contributors to customer satisfaction and determining whether more complex models outperform simpler models.

## Deliverables
- Cleaned dataset
- Trained predictive models
- Model comparison results
- Final project report and presentation

## Implications
This project addresses a key challenge in predicting product success before launch by using data-driven methods. The primary target audience is product developers and marketing teams in cosmetic companies.

These stakeholders can use the results of this project to:
- Optimize product design
- Improve pricing strategies
- Reduce the risk of failed product launches
- Make more data-driven business decisions

This project also demonstrates how machine learning can be applied to customer analytics beyond the beauty industry.

For the team, this project provides practical experience in:
- Data preprocessing
- Model development
- Predictive analysis

These are valuable skills for future careers in data science and analytics.

## Conclusion
In conclusion, this project aims to use a data-driven approach to predict customer review ratings for beauty products. By applying machine learning models, we aim to identify the key factors that influence customer satisfaction while producing a model with predictive capability.

This proposal outlines our planned approach, but we will remain flexible and refine our methods as we gain further insights from the data.
