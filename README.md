## Car Insurance Analysis and Claim Prediction Using Machine Learning Models
   
### Abstract
Insurance operates as a financial transaction, exchanging uncertain future losses for certain premiums. In this exchange, an insured event triggers a request for coverage, constituting an insurance claim. Accurately anticipating these claims is crucial for insurers, shaping pricing accuracy and future profitability projections. A precise understanding of claims occurrence profoundly influences an insurance company’s operational profitability, underpinning pricing validity and risk assessment for solvency requirements. 

Traditional forecasting methods rely on historical patterns and probability distributions, distinguishing between small and large claims to refine predictions. Amidst this landscape, harnessing the power of cutting-edge machine learning methodologies like XGBoost, Logistic Regression, and Support Vector Machines (SVM) represents an evolutionary leap. Employing these advanced models enables a deeper understanding of intricate data patterns, fosters nuanced risk assessments, and amplifies predictive accuracy. The impact of these ML models spans claims processing, fraud detection, risk management, and most importantly, claim capability of predicting insurance claims with precision.

### Introduction
A dataset on annual car insurance claims by customers, for a specific company, has been provided on Kaggle - the link is provided in the References section below. The dataset has 19 columns. Among these columns are 18 independent features, spanning numerical and non-numerical data, while the remaining column represents a binary numerical dependent variable. Notably, the dataset exhibits an imbalance, with a ratio of 0.7 for "Not claimed" instances compared to 0.3 for "Claimed" instances. Our objective involves discerning underlying data trends and leveraging machine learning algorithms to train models capable of predicting, with reasonable accuracy, whether a customer will file a future claim based on specific features such as age, car ownership, and income. 

It is a classification problem, which falls under the umbrella of supervised learning methods. We will use the following ML models for this classification task: Logistic Regression, XGBoost, SVMs, KNN, and Neural Networks. Given the inherent imbalance, our assessment will prioritize "recall" as the scoring metric, emphasizing the model's proficiency in correctly identifying all relevant instances, particularly positive outcomes within this context.

### References and Related Work
- Link to the dataset: https://www.kaggle.com/datasets/sagnik1511/car-insurance-data
- Thomas et al. Machine Learning in Forecasting Motor Insurance Claims, 2023 - https://www.mdpi.com/2227-9091/11/9/164
- Baran et al. Prediction of motor insurance claims occurrence as an imbalanced machine learning problem - https://arxiv.org/abs/2204.06109

### In this repository:
- Click on the `main.ipynb` to view the working behind our models and explanations
- The link to the dataset: [click here](https://www.kaggle.com/datasets/sagnik1511/car-insurance-data)
