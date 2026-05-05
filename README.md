# 🏥 Support Vector Machines (SVM) - Health Diagnosis Prediction

## 📌 Overview
This project uses **Support Vector Machines (SVM)** to predict a patient's health diagnosis based on medical attributes such as blood pressure, cholesterol, BMI, and glucose levels.

The goal is to build a classification model that can accurately distinguish between different health conditions using machine learning techniques.

---

## 📂 Project Structure
```
├── SVM.ipynb              # Main notebook with implementation
├── health_dataset.csv     # Dataset used for training and testing
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

---

## 📊 Dataset

The dataset (`health_dataset.csv`) contains medical records with the following features:

| Feature            | Description                          |
|------------------|--------------------------------------|
| blood_pressure   | Patient's blood pressure level       |
| cholesterol      | Cholesterol level                    |
| bmi              | Body Mass Index                      |
| glucose          | Blood glucose level                  |
| diagnosis        | Target variable (e.g., Healthy/Other)|

### 🧾 Sample Data:
```
blood_pressure | cholesterol | bmi     | glucose  | diagnosis
-------------------------------------------------------------
120.46         | 159.02      | 25.28   | 82.06    | Healthy
101.72         | 171.71      | 23.01   | 98.63    | Healthy
105.30         | 128.30      | 23.48   | 106.98   | Healthy
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Install dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 3️⃣ Run the notebook
```bash
jupyter notebook SVM.ipynb
```

---

## 🔍 Workflow

### ✔ Data Preprocessing
- Loaded dataset  
- Checked for missing values  
- Encoded target variable (`diagnosis`)  
- Applied feature scaling (StandardScaler)  
- Train-test split  

### ✔ Exploratory Data Analysis (EDA)
- Distribution of health metrics  
- Correlation analysis  
- Outlier detection using boxplots  

### ✔ Model Training
- Linear SVM  
- Polynomial Kernel SVM  
- RBF Kernel SVM  

### ✔ Hyperparameter Tuning
- Optimized:
  - C (regularization parameter)  
  - gamma  
  - kernel type  
- Used GridSearchCV  

### ✔ Model Evaluation
- Accuracy  
- Precision, Recall, F1-score  
- Confusion Matrix  

---

## 📊 Results & Insights
- Feature scaling significantly improved model performance  
- SVM effectively separates health conditions based on medical features  
- RBF kernel performed better for complex patterns in the data  

---

## 🛠️ Technologies Used
- Python  
- Scikit-learn  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Jupyter Notebook  

---

## 🚀 Future Improvements
- Add more medical features for better prediction  
- Try other models (Logistic Regression, Random Forest, XGBoost)  
- Deploy as a health prediction web app  

---

## ⚠️ Disclaimer
This project is for educational purposes only and should not be used for real medical diagnosis.

---

## ⭐ Support
If you found this project useful, give it a ⭐ on GitHub!
