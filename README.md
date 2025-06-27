# Decision Tree vs Random Forest House Price Prediction
This notebook explores and compares Decision Tree and Random Forest models for predicting house prices in Melbourne. It includes hyperparameter optimization using GridSearchCV to improve model accuracy and reduce prediction error.

## 📦 Technologies Used
- `pandas` — Data handling and manipulation.

- `numpy` — Numerical operations.

- `scikit-learn` — For machine learning models, metrics, train-test split, and GridSearchCV.
  
## 📜 Installation

First, make sure you have Python 3 installed. Then, install the required dependencies:

```bash
pip install pandas numpy scikit-learn
```

## 🚀 How to Use
1. Open the notebook file:
```bash
DecisionTree_vs_RandomForest_HousePricePrediction.ipynb
```

2. Upload your dataset

- Option 1: Upload your dataset to your Google Drive.

- Option 2: Place your dataset in a local directory if running locally.

3. Set the correct dataset path
In the notebook, locate the following code and update the ruta variable with your dataset path:
```bash
ruta = "/content/drive/MyDrive/Proyects/Melb_Modelo/melb_data.csv"
```
📌 Replace /content/drive/MyDrive/Proyects/Melb_Modelo/melb_data.csv with the actual path where your dataset is stored.

4. Run all the Notebook

## 🎯 Summary
Initial Decision Tree model showed signs of overfitting.

Random Forest outperformed Decision Tree in both raw error and relative error.

After hyperparameter optimization with GridSearchCV, the Random Forest model achieved a Mean Absolute Error (MAE) of around 17.78% relative to the mean house price — a solid result for this type of regression problem.

## 📊 Dataset
The dataset used in this project is the Melbourne Housing Market dataset.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

## ✨ Author
Developed by Jonathan Estiven Fontalvo Aparicio 📧

Feel free to copy this into your repo. If you'd like to contribute or help, just let me know!

