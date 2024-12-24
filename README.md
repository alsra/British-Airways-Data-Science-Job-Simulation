# British-Airways-Data-Science-Job-Simulation

![British Airways Logo](https://www.google.com/url?sa=i&url=https%3A%2F%2Fmediacentre.britishairways.com%2Fimage%2Fdetails%2F115864&psig=AOvVaw0gEAk0XdwNVeYfPfRL_AKb&ust=1735164916049000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCJDiwry3wYoDFQAAAAAdAAAAABA6)

This project focuses on analyzing customer reviews from the British Airways page on Airline Quality and predicting customer buying behavior using machine learning techniques.

---
## Introduction
This project is divided into two main tasks:
1. Conducting sentiment analysis on British Airways customer reviews to classify them as positive or negative.
2. Building a classification model to predict customer buying behavior based on structured data.

---

## Task 1: Sentiment Analysis
The customer reviews were retrieved from the [British Airways page on Airline Quality](https://www.airlinequality.com/airline-reviews/british-airways).

- Web scraping was performed to collect unstructured data.
- Text preprocessing techniques (e.g., tokenization, stop-word removal) were applied.
- Sentiment analysis was conducted to classify reviews as positive or negative.
- Insights and analysis were summarized in a PowerPoint presentation.

---
### Challenges
The dataset exhibited a significant class imbalance, making it difficult for models to accurately predict positive class instances.

### Approach
- Implemented several classification models.
- Performed cross-validation and hyperparameter tuning to optimize model performance.
- Used SMOTE (Synthetic Minority Over-sampling Technique) to address the class imbalance.

### Best Performing Model
- **Model**: XGBoost
- **Metrics**:
  ![Metrics](https://github.com/alsra/British-Airways-Data-Science-Job-Simulation/blob/main/best_model.png)
---
## Observations
- All models struggled with accurately predicting the positive class due to class imbalance.
- Predictions were skewed towards the majority class, impacting the ability to generalize.
- SMOTE helped improve the model's performance in handling the positive class, but the results were still suboptimal.

---
## Certificate
[View Certificate](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/tMjbs76F526fF5v3G/NjynCWzGSaWXQCxSX_tMjbs76F526fF5v3G_MR7ApHK7eMzT9mSxY_1735077756198_completion_certificate.pdf)
