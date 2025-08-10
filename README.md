# Churn Prediction Model

The goal of building this repo was to improve my data science skills by working with the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data).

## Key Takeaways

Below are the list of things I learnt from this project:
- How to **analyze data distributions and make assumptions based on statistical values**
- How to **preprocess mixed data types** for numeric scaling and categorical encoding
- How to **build end-to-end ML pipelines** combining preprocessing and modelling
- How to perform basic **hyperparameter tuning and cross-validation**
- Techniques to avoid commong pitfalls such as **getting rid of multicollinearity introduced by one-hot encoding**
- **Saving and loading pipelines using joblib for reproducibility and deployment-readiness**

## Personal Reflections

This was my first time attempting an end-to-end ML pipeline for a personal project. There were some challenges I faced - working with categorical data, avoiding data leakage, hyperparameter tuning to improve model performance, and more.

One of the biggest things I learnt from this project was to understand the data you're working with and **who** your results are meant for.

I had gone into this project with the idea of deploying my model on AWS. However, towards the end of the project I realized that the conclusions would derive from a customer churn model would be meant for internal business use only, so deploying it to AWS would be unnecessary costs and introduce extra complexity for no reason.