# 🚢 Titanic Survival Prediction (Machine Learning Project)

## 📌 Project Overview

This project predicts whether a passenger survived the Titanic disaster using Machine Learning.
A complete ML pipeline is built including data preprocessing, model training, evaluation, and deployment.

## ⚙️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Scikit-learn
* Matplotlib & Seaborn

## 📊 Dataset

* Titanic Dataset (CSV)
* Features used:

  * Pclass
  * Sex
  * Age
  * SibSp
  * Parch
  * Fare
  * Embarked

## 🧠 Model Details

* Algorithm: Logistic Regression
* Preprocessing:

  * Missing values handled (Median & Most Frequent)
  * One-Hot Encoding for categorical features
  * Standard Scaling for numerical features
* Pipeline used for automation

## 📈 Model Performance

* Accuracy: ~77%
* ROC-AUC Score: ~0.84
* Model performs better on non-survivors than survivors

## 🔁 Cross Validation

* 5-Fold Cross Validation performed
* Mean ROC-AUC: ~0.84
* Model shows consistent performance

## 💾 Model Saving

* Model saved using `joblib`
* File: `model.joblib`

## 📂 Project Structure

* Titanic Notebook (.ipynb)
* model.joblib
* images folder

## 🚀 Key Takeaways

* Gender and passenger class strongly influence survival
* Logistic Regression provides a simple and effective baseline
* Model is stable but can be improved with advanced algorithms

## 🔮 Future Improvements

* Use advanced models like Random Forest / XGBoost
* Feature engineering
* Hyperparameter tuning

## Author  
Jagriti Sethi 

