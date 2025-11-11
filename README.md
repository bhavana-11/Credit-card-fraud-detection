# Credit Card Fraud Detection

This project detects fraudulent credit card transactions using machine learning and deep learning models.  
It compares anomaly detection methods such as Isolation Forest, LOF, One-Class SVM, and Autoencoders.

## Dataset
Kaggle Credit Card Fraud Dataset (284,807 transactions)

## Models Used
- Isolation Forest
- Local Outlier Factor (LOF)
- One-Class SVM
- Autoencoder (Deep Learning)

## Results
- Achieved up to **99% Accuracy**
- **84% Recall** for fraud detection (prioritizing catching fraud cases)
- Reduced false negatives by ~80%

## How to Run
pip install requirements.txt


## Requirements
See `requirements.txt` for dependencies.

## Future Improvements
- Deploy model via FastAPI
- Add real-time streaming detection
- UI dashboard for monitoring
