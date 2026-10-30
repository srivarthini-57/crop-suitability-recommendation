# Crop Suitability Recommendation Using Machine Learning

## Project Overview

This project was completed as part of my MSc Business Analytics dissertation at Coventry University. It explores how soil nutrient and climatic conditions can be used to predict crop suitability through supervised machine learning.

The study focuses on seven environmental variables: nitrogen (N), phosphorus (P), potassium (K), temperature, humidity, pH and rainfall. It also examines classification performance and patterns of misclassification, particularly between Rice and Jute.

## Dataset

The study uses a publicly available crop recommendation dataset with the following characteristics:

- **Total observations:** 2,200
- **Crop categories:** 22
- **Records per crop:** 100
- **Predictor variables:** 7
- **Missing values:** None reported

## Tools and Technologies

- WEKA 3.8.7
- Information Gain Attribute Evaluation
- J48 Decision Tree
- Random Forest
- Naïve Bayes

## Methodology

The analysis was conducted using WEKA and included:

1. Dataset exploration and data quality checks.
2. Feature evaluation using Information Gain.
3. Classification using J48, Random Forest and Naïve Bayes.
4. Model validation using 10-fold cross-validation.
5. Performance evaluation using accuracy, precision, recall, F1-score, Kappa statistics and confusion matrices.
6. Misclassification analysis to identify frequently confused crop categories.

## Model Performance

The three models achieved the following overall accuracy:

| Classification Model | Accuracy |
|---|---:|
| J48 Decision Tree | 99.1364% |
| Random Forest | 99.3636% |
| Naïve Bayes | 99.5000% |

Naïve Bayes achieved the highest accuracy in this experiment.

## Key Findings

- Humidity had the highest Information Gain, followed by rainfall and potassium.
- All three classification models achieved accuracy above 99%.
- Rice and Jute were repeatedly confused across the three models.
- The observed misclassification patterns highlighted the importance of overlapping environmental conditions when interpreting crop predictions.

## Limitations

The study uses a single secondary dataset and a limited set of environmental predictors. Its findings should therefore be interpreted within the context of the dataset and selected modelling methods. Formal uncertainty quantification and direct measurement of financial or supply chain impacts were not undertaken.

## Project Purpose

This research demonstrates the application of business analytics and machine learning to an agricultural decision-support problem. It also considers how classification errors may be relevant to agricultural planning, including seed procurement, fertiliser allocation and planting decisions.

---

**Academic project:** MSc Business Analytics  
**Institution:** Coventry University  
**Software:** WEKA 3.8.7