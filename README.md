# online-payment-fraud
# Online Payment Fraud Detection

## Overview
This project aims to detect fraudulent online payment transactions using machine learning techniques. The provided code implements various classification models to predict whether a transaction is fraudulent based on features such as transaction type, amount, and time step.

## Dataset
The dataset used for this project is stored in the `onlinefraud.csv` file. It contains information about online payment transactions, including features like transaction type, amount, time step, and whether the transaction is fraudulent or not.

## Setup
1. Clone the repository:
git clone https://github.com/your-username/online-payment-fraud-detection.git

2. Install the required dependencies:
pip install -r requirements.txt

3. Run the `fraud_detection.py` script to train and evaluate the fraud detection models.

## Code Structure
- `fraud_detection.py`: Main script for data preprocessing, model training, and evaluation.
- `onlinefraud.csv`: Dataset containing online payment transaction records.
- `README.md`: Overview and instructions for running the project.

## Model Selection
The following classification models are implemented and evaluated for fraud detection:
- Logistic Regression
- XGBoost
- Random Forest
- Support Vector Classifier (SVC)
- Histogram-based Gradient Boosting Classifier

## Evaluation Metrics
Model performance is evaluated using the ROC AUC score, which provides insights into the model's ability to distinguish between fraudulent and non-fraudulent transactions.

## Results
The trained models are evaluated on both training and testing datasets to assess their performance. Model performance metrics such as training accuracy and validation accuracy are reported for each model.

## Next Steps
- Hyperparameter tuning: Fine-tune model parameters to optimize performance.
- Model deployment: Deploy the trained models for real-time fraud detection in production environments.
- Model monitoring: Continuously monitor model performance and update models to adapt to evolving fraud patterns.

## Contributors
- Nakshatra Paul

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

