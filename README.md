# amazon-product-recommendation-system
# Amazon Product Recommendation System

## Project Overview

This project explores recommendation system techniques using Amazon electronic product ratings. The objective is to analyze historical user-product interactions and develop models capable of generating personalized product recommendations.

The analysis compares popularity-based recommendations, similarity-based collaborative filtering, and matrix factorization to evaluate their effectiveness in identifying relevant products for users.

## Business Objectives

- Analyze user-product rating patterns and distributions.
- Identify popular products based on customer ratings.
- Develop personalized product recommendation models.
- Compare user-user and item-item collaborative filtering approaches.
- Apply matrix factorization using Singular Value Decomposition (SVD).
- Evaluate recommendation quality using ranking and prediction metrics.
- Optimize model performance through hyperparameter tuning.

## Tools & Technologies

- **Programming:** Python
- **Data Analysis:** Pandas, NumPy
- **Recommendation Systems:** Surprise
- **Machine Learning:** Collaborative Filtering, K-Nearest Neighbors, Singular Value Decomposition
- **Model Evaluation:** Precision@K, Recall@K, F1-score@K, RMSE
- **Environment:** Google Colab / Jupyter Notebook

## Methodology

The project follows a structured recommendation system development process:

1. Data loading and preprocessing.
2. Exploratory data analysis.
3. Popularity-based recommendation modeling.
4. User-user collaborative filtering.
5. Item-item collaborative filtering.
6. Matrix factorization using SVD.
7. Model evaluation and comparison.
8. Hyperparameter optimization.
9. Final model assessment and recommendations.

## Model Evaluation

Recommendation models were evaluated using:

- **Precision@K:** Measures the proportion of recommended products that are relevant.
- **Recall@K:** Measures the proportion of relevant products successfully recommended.
- **F1-score@K:** Balances precision and recall.
- **RMSE:** Measures the difference between predicted and actual product ratings.

## Key Findings

- Item-item collaborative filtering improved recommendation performance compared with its baseline model.
- The optimized item-item model achieved a Recall@10 of 0.8927 and an F1-score@10 of 0.8601.
- The SVD matrix factorization model achieved an RMSE of 0.9104 in its baseline version.
- Hyperparameter tuning produced modest improvements in the SVD model's evaluation metrics.
- SVD was able to generate predictions for user-product combinations where similarity-based approaches encountered insufficient neighboring data.

## Business Applications

Recommendation systems can help e-commerce businesses personalize product discovery, improve customer engagement, and identify products that align with individual customer preferences.

## Repository Contents

| File | Description |
|---|---|
| `amazon_product_recommendation_portfolio.ipynb` | Jupyter Notebook containing the analysis, recommendation models, evaluation, and findings. |

## Project Background

This project originated as part of my data science coursework and is included in my professional portfolio to demonstrate practical experience with Python, recommendation algorithms, collaborative filtering, and model evaluation.

## Author

GitHub: https://github.com/peregoy-tech
