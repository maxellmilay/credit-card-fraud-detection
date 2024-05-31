# Credit Card Fraud Detection

## Results

### Fraud Detection

| Model | Distribution | Dataset| Precision | Recall | F-1 Score |
| --- | --- | --- | :---: | :---: | :---: |
| Logistic Regression | Imbalanced | Validation | 0.83 | 0.28 | 0.42 |
| Shallow Neural Network | Imbalanced | Validation | 0.75 | 0.67 | 0.71 |
| Random Forest | Imbalanced | Validation | 0.89 | 0.44 | 0.59 | 
| Gradient Boosting | Imbalanced | Validation | 0.71 | 0.56 | 0.62 |
| Support Vector Machine | Imbalanced | Validation | 0.77 | 0.56 | 0.65 |
| Logistic Regression | Balanced | Validation | 1.00 | 0.91 | 0.96 |
| Shallow Neural Network - 2 ReLU | Balanced | Validation | 1.00 | 0.91 | 0.96 |
| Shallow Neural Network - 1 ReLU | Balanced | Validation | 1.00 | 0.87 | 0.93 |
| Random Forest | Balanced | Validation | 1.00 | 0.87 | 0.93 |
| Gradient Boosting | Balanced | Validation | 0.94 | 0.93 | 0.94 |
| Support Vector Machine | Balanced | Validation | 0.98 | 0.93 | 0.96 |

### Not Fraud Detection

| Model | Distribution | Dataset| Precision | Recall | F-1 Score |
| --- | --- | --- | :---: | :---: | :---: |
| Logistic Regression | Balanced | Validation | 0.92 | 1.00 | 0.96 |
| Shallow Neural Network - 2 ReLU | Balanced | Validation | 0.92 | 1.00 | 0.96 |
| Shallow Neural Network - 1 ReLU | Balanced | Validation | 0.89 | 1.00 | 0.94 |
| Random Forest | Balanced | Validation | 0.89 | 1.00 | 0.94 |
| Gradient Boosting | Balanced | Validation | 0.93 | 0.94 | 0.94 |
| Support Vector Machine | Balanced | Validation | 0.93 | 0.99 | 0.96 |

## Data

The dataset csv was not pushed to this repository since it exceeded 100 MB. It can be downloaded [here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) instead