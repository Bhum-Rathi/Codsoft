# Titanic Survival Prediction 🚢

## 📌 Project Overview
This is a **Machine Learning classification project** where the goal is to predict whether a passenger survived the Titanic disaster or not using historical passenger data.

The project follows the complete ML workflow including data preprocessing, model training, evaluation, and visualization.

---

## 📊 Dataset
The dataset used is the **Titanic dataset**, which contains details of passengers such as:
- Passenger Class (Pclass)
- Gender (Sex)
- Age
- Fare
- Embarked
- Survival Status (Target Variable)

Target Variable:
- 0 → Not Survived  
- 1 → Survived  

---

## ⚙️ Technologies & Libraries Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🧹 Data Preprocessing
The following preprocessing steps were performed:
- Missing values handled:
  - Age filled using median
  - Embarked filled using mode
- Dropped unnecessary column (`Cabin`)
- Converted categorical variables into numerical form (Encoding)
- Split dataset into training and testing sets (80% train, 20% test)

---

## 🤖 Machine Learning Model
- **Random Forest Classifier** was used to train the model and make predictions.

---

## 📈 Model Evaluation
- **Accuracy:** ~70%

### Confusion Matrix:
