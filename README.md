# 🫀 Heart Disease Prediction using Machine Learning

This project was completed as part of the Data Science and Machine Learning Internship Program at Edureka. It focuses on predicting the probability of a person having heart disease or a heart attack using real-world health indicators and standard machine learning techniques.

---

## 📌 Problem Context

Heart disease is the leading cause of death in the United States, claiming over 647,000 lives each year. Early diagnosis and prevention play a critical role in reducing this burden. This project aims to predict heart disease risk based on key lifestyle, demographic, and clinical variables using a machine learning approach.

**Dataset Source**: [Kaggle - Heart Disease Health Indicators](https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset)

---

## 🎯 Project Objectives

- Build a machine learning model to classify patients at risk of heart disease or heart attack.
- Identify the most influential health features using `feature_importances_` from tree-based models.
- Handle class imbalance using both random oversampling and undersampling.
- Compare and evaluate model performance using classification metrics and precision-recall curves.
- Build a clean, reusable ML pipeline for reproducibility.

---

## 📊 Dataset Highlights

- `HeartDiseaseorAttack`: Target variable (1 = Yes, 0 = No)
- `HighBP`, `HighChol`, `Smoker`, `Diabetes`: Key risk flags
- `BMI`, `MentHlth`, `PhysHlth`: Continuous health metrics
- `Fruits`, `Veggies`, `HvyAlcoholConsump`: Lifestyle habits
- `Sex`, `Age`, `Education`, `Income`: Demographics

---

## ⚙️ Tools & Technologies

- **Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
- **Techniques**:
  - Random Oversampling & Undersampling
  - Logistic Regression
  - Random Forest Classifier
  - Gradient Boosting Classifier
  - `feature_importances_` for key driver analysis
  - ML Pipeline with `Pipeline()` from Scikit-learn

---

## 🚀 Workflow Summary

1. Data Preprocessing & Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Class Imbalance Handling (Over/Undersampling)  
5. Model Building (Logistic Regression, RF, Gradient Boosting)  
6. Evaluation on Hold-Out Test Set  
7. Feature Importance Ranking  
8. Pipeline Construction  

---

## 📈 Results & Insights

- **Gradient Boosting** performed best in terms of AUC and precision-recall tradeoff.
- Feature importance revealed top risk indicators like `Age`, `BMI`, `Income`, and `PhysHlth`.
- Class imbalance was effectively addressed through sampling techniques.
- Pipeline design ensures reproducibility and modularity for deployment.

---

## 📁 Project Structure

```
📦 Heart-Disease-Prediction
├── Heart_Disease_Prediction.ipynb
├── README.md
├── Heart_Disease_Dataset.csv
├── Requirements.txt
```

---

## 💻 How to Run This Project

1. Clone the repo  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run:  
   `Heart_Disease_Prediction.ipynb`

---

## 📚 Acknowledgements

- Dataset: CDC via Kaggle  
- Internship & Mentorship: Edureka – Data Science & ML Program

---

## 👨‍💻 Author

**Konduru Jayanth**  
📧 jayanthkonduru1@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/kondurujayanth) | [GitHub](https://github.com/kondurujayanth)
