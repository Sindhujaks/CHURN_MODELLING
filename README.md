# Churn Prediction using Artificial Neural Networks (ANN)

## Overview
Customer churn is a critical concern for businesses, as retaining existing customers is often more cost-effective than acquiring new ones. This project aims to predict customer churn using an Artificial Neural Network (ANN) model. The model is trained on a dataset containing customer demographics, account information, and activity history to determine the likelihood of churn.

## 📂 Dataset
- The dataset contains customer information such as age, location, balance, number of products, and activity levels.
- Features include numerical and categorical data, which are preprocessed for the ANN.
- The target variable is **Churn (1: Yes, 0: No)**.
- Dataset source: *Publicly available churn dataset in Kaggle.*

### 📥 Download Dataset
```python
import kagglehub

# Download latest version
path = kagglehub.dataset_download("shrutimechlearn/churn-modelling")

print("Path to dataset files:", path)
```

## 📊 Technologies Used
- **Python** (Pandas, NumPy, Matplotlib)
- **Keras** (for ANN implementation)
- **Scikit-Learn** (for preprocessing & evaluation)
- **Jupyter Notebook / Google Colab** (for experimentation)

