# Credit Card Fraud Detection Using ML

Digital payment systems have grown rapidly over the past decade, bringing convenience but
also increasing the risk of credit card fraud. Fraudulent transactions are rare and often
hidden within thousands of normal transactions, making manual detection almost
impossible.

This project focuses on building a machine learning-based fraud detection model
using the publicly available Kaggle credit card dataset. The work involves data preprocessing,
handling class imbalance using SMOTE, and training a Random Forest classifier to distinguish
fraudulent transactions from legitimate ones. Although other algorithms such as XGBoost
were considered, Random Forest demonstrated a stable performance and was selected for
the final model.

Various evaluation metrics including precision, recall, F1-score, ROC-AUC, PR-AUC, and
confusion matrix are used to assess the model’s effectiveness. The results show that the
model achieves high recall and strong discrimination capability, which is crucial for fraud
detection where missing a fraud is more dangerous than raising a false alarm. The project
also includes visualizations, threshold tuning, and analysis of trade-offs between precision
and recall. The final outcome is a functional fraud detection model that can flag suspicious
transactions with good accuracy.
