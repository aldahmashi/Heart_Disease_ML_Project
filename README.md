# ❤️ Heart Disease Prediction using Machine Learning

This project builds a complete end-to-end machine learning pipeline to predict heart disease using the UCI Heart Disease dataset. It includes Exploratory Data Analysis (EDA), preprocessing, model training, ROC–AUC evaluation, and feature importance analysis. The notebook is fully documented with clear explanations for each step.

---

## 📊 Project Overview

The goal of this project is to analyze medical data and build machine learning models that can accurately predict whether a patient has heart disease. The workflow includes:

- Data loading and inspection  
- Exploratory Data Analysis (EDA)  
- Outlier detection using boxplots  
- Feature scaling  
- Train/test split  
- Training multiple ML models  
- Model evaluation using accuracy, precision, recall, F1-score  
- ROC Curve + AUC comparison  
- Feature importance analysis  

---

## 🚀 Machine Learning Models Used

- **Logistic Regression**  
- **Random Forest Classifier**  
- **Support Vector Machine (SVM)**  

All models achieved strong performance with **AUC ≈ 0.93**, showing excellent ability to distinguish between patients with and without heart disease.

---

## 📈 Key Insights

- **cp (chest pain type)** and **oldpeak** show strong relationships with heart disease.  
- **ca (number of major vessels)** is the most important feature in the Random Forest model.  
- **fbs** and **restecg** contribute very little to prediction.  
- The dataset is balanced and clean, requiring minimal preprocessing.

---

## 🧠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📂 Files in This Repository

- `heart_disease_project.ipynb` — Main notebook  
- `README.md` — Project documentation  
- `.gitignore` — Python ignore rules  
- `LICENSE` — MIT License  

---

## ▶️ How to Run the Project

1. Clone the repository:
git clone https://github.com/aldahmashi/Heart_Disease_ML_Project.git
2. Open the notebook in Jupyter or Google Colab  
3. Run all cells in order  

---

## 🏁 Conclusion

This project demonstrates a full machine learning workflow and provides meaningful insights into medical risk factors for heart disease. The models perform strongly and generalize well, making this a solid foundation for further improvements such as hyperparameter tuning or deployment.

---

## 👤 Author

**Nasser Aldahmashi**  
ML & AI Student  
