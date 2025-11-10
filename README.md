# 🚢 Titanic Survival Prediction

This project predicts the survival of passengers aboard the Titanic using various Machine Learning algorithms. The goal is to analyze passenger data (age, gender, ticket class, etc.) and determine the likelihood of survival.

---

## 🧠 Project Overview
The Titanic dataset is one of the most famous datasets used for learning data science and machine learning. This project builds predictive models to classify whether a passenger survived or not, based on features such as:
- Age  
- Sex  
- Passenger Class (Pclass)  
- Fare  
- Embarked  
- Number of Siblings/Spouses (SibSp)  
- Number of Parents/Children (Parch)

---

## 📂 Dataset
The dataset used is from the **Kaggle Titanic: Machine Learning from Disaster** competition.  
You can find it here: [Titanic Dataset on Kaggle](https://www.kaggle.com/c/titanic/data)

Files used:
- `train.csv` – Training data
- `test.csv` – Test data
- `gender_submission.csv` – Sample submission file

---

## ⚙️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🧹 Data Preprocessing
Steps performed before training the model:
1. Handled missing values (Age, Embarked, etc.)
2. Converted categorical variables to numerical (Sex, Embarked)
3. Feature scaling and normalization
4. Train-test split for model evaluation

---

## 🤖 Machine Learning Models
Several ML algorithms were trained and compared:
- Logistic Regression  
- Random Forest Classifier  
- Decision Tree Classifier  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  

The best model was selected based on **accuracy** and **cross-validation performance**.

---

## 📈 Model Evaluation
Models were evaluated using metrics like:
- Accuracy Score  
- Confusion Matrix  
- Classification Report  
