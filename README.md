# Amazon Reviews Sentiment Analysis

This project demonstrates an end-to-end sentiment analysis on Amazon product reviews using both classical machine learning and deep learning models. It includes data preprocessing, model training, evaluation, explainability, and an analysis of negative reviews.

## Features

- **Data Preprocessing:** Processed 4M+ Amazon reviews using **PySpark** and applied tokenization for transformer models.  
- **Baseline Model:** Trained a **Logistic Regression** model using **TF-IDF features** (scikit-learn).  
- **Deep Learning Model:** Fine-tuned **DistilBERT** for sentiment classification using **PyTorch**. 
- **Model Evaluation:** Evaluated models using metrics like **accuracy** and **ROC-AUC**. Achieved **0.89 accuracy for LR** and **0.95 accuracy for fine-tuned DistilBERT**.  
- **Explainability:** Applied **SHAP** to identify influential tokens impacting model predictions.  
- **Zero-Shot Analysis:** Used **Hugging Face zero-shot classification** to categorize negative reviews, discovering that **47% of negative reviews were due to product quality issues**.  
