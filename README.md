# Sampling Assignment
# Sneha (102303723)

## Objective
- Study the effect of sampling techniques on an imbalanced credit card fraud dataset  
- Compare performance of multiple ML models on balanced data  
- Identify the best sampling method for each model  

## Methodology
- Loaded imbalanced credit card dataset  
- Applied five sampling techniques:  
  - Random UnderSampling  
  - Random OverSampling  
  - SMOTE  
  - SMOTE-Tomek  
  - NearMiss  
- Trained five ML models on each sampled dataset:  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - KNN  
  - Naive Bayes  
- Calculated accuracy for every model–sampling combination  
- Selected best sampling based on highest accuracy  

## Results

Accuracy comparison of models across sampling techniques:

| Model | Sampling1 | Sampling2 | Sampling3 | Sampling4 | Sampling5 |
|------|-----------|-----------|-----------|-----------|-----------|
| Logistic Regression | 33.33 | 91.92 | 91.92 | 92.79 | 50.00 |
| Decision Tree | 50.00 | 98.69 | 98.25 | 97.97 | 16.67 |
| Random Forest | 33.33 | 100.00 | 99.34 | 99.55 | 16.67 |
| KNN | 33.33 | 98.47 | 83.84 | 86.71 | 83.33 |
| Naive Bayes | 33.33 | 74.67 | 87.77 | 82.66 | 33.33 |


**Best Sampling Technique per Model:**

- Logistic Regression → Sampling4  
- Decision Tree → Sampling2  
- Random Forest → Sampling2  
- KNN → Sampling2  
- Naive Bayes → Sampling3  

## Conclusion
- Sampling significantly affects classification on imbalanced data  
- No single sampling method is best for all models  
- SMOTE and Random OverSampling generally improved performance for complex models  
- Sampling choice should depend on the ML algorithm
