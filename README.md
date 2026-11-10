
# Data Management for Machine Learning – Assignment 2

## End-to-End Data Management Pipeline for a Recommendation System

**Submitted by:** Putta Madhu Rani

**Roll Number:** 2025AG05144

## 1. Project Overview

This project implements an end-to-end data management
pipeline for an e-commerce recommendation system.

The pipeline includes data ingestion, validation,
data preparation, feature engineering, model training,
model evaluation and workflow orchestration.

## 2. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 3. Dataset Description

Synthetic datasets were generated for this project.

| Dataset | Records | Columns |
|---------|---------|---------|
| Users | 500 | 4 |
| Items | 200 | 4 |
| Interactions | 12000 | 6 |

## 4. Pipeline Stages

1. Data Ingestion
2. Data Validation
3. Data Cleaning and Preparation
4. Feature Engineering
5. Train/Test Splitting
6. Recommendation Model Training
7. Model Evaluation
8. Workflow Orchestration

## 5. Recommendation Models

### Model 1: Popularity-Based Recommendation

Recommends products based on their interaction counts.

### Model 2: Item-Based Collaborative Filtering

Uses cosine similarity to generate personalized
recommendations based on user-item ratings.

## 6. Evaluation Results

| Metric | Popularity-Based | Collaborative Filtering |
|--------|------------------|-------------------------|
| Precision@10 | 0.012297 | 0.010441 |
| Recall@10 | 0.048884 | 0.045343 |
| NDCG@10 | 0.024728 | 0.026468 |
| Coverage | 0.085 | 1.000 |
| Diversity | 0.856458 | 0.809126 |

## 7. Conclusion

Both recommendation models were successfully trained
and evaluated.

The popularity-based model achieved higher precision,
recall and diversity.

The item-based collaborative filtering model achieved
higher NDCG and catalog coverage.

The complete workflow executed successfully.

## 8. Author

Putta Madhu Rani

Roll Number: 2025AG05144
