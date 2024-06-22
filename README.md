# Uber Data ANalysis
Objective:

The goal is to conduct exploratory data analysis on the dataset to uncover hidden or previously unknown information. This involves understanding how each field in the dataset influences the 'Price' variable in relation to other fields. Subsequently, various machine learning models are applied to the data to conduct a thorough analysis. The performance of these models is evaluated based on accuracy, and the best-performing model is recommended for future predictions of the 'Price' label.


Conclusion:

Before proceeding with feature engineering, it's crucial to gain insights from the data through exploratory data analysis (EDA). Visualization of the dataset using various plots revealed several key observations: the absence of taxi price data, variations in prices across different types of cabs and weather conditions, and the distribution of categorical variables. Categorical values were converted to a continuous format, and missing price values were imputed using the median of available data. Feature selection was then performed using recursive feature elimination (RFE), resulting in the identification of the top 25 features. After dropping less impactful features, 8 important columns remained. Four different models were applied to the refined dataset, with Decision Tree, Random Forest, and Gradient Boosting Regressor demonstrating over 96% accuracy during training. Ultimately, Random Forest was chosen for its resilience against overfitting. A predictive function based on the Random Forest model was developed to forecast prices effectively.
