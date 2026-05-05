# 🚀 Support Vector Machines (SVM) Project

## 📌 Overview
This project demonstrates the implementation of Support Vector Machines (SVM) for classification tasks using the Iris Flower Dataset. It explores how different kernel functions impact model performance and decision boundaries.

The objective is to build, evaluate, and compare multiple SVM models to achieve optimal classification accuracy.

---

## 📂 Project Structure
```
├── data/                  # Dataset used for training and testing
├── notebooks/             # Jupyter notebooks with step-by-step implementation
├── src/                   # Python scripts for training & evaluation
├── results/               # Model outputs and performance metrics
├── visualizations/        # Plots and graphs
├── README.md              # Project documentation
└── requirements.txt       # Dependencies
```

---

## 📊 Dataset
The project uses the Iris Flower Dataset, consisting of 150 samples from three species:

- Iris Setosa  
- Iris Versicolor  
- Iris Virginica  

### 🔢 Features:
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/27abhishek27/Support-Vector-Machines-Project.git
cd Support-Vector-Machines-Project
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

---

## 🔍 Methodology

### 1. Data Preprocessing
- Checked and handled missing values  
- Applied feature scaling (Standardization)  
- Performed train-test split  

### 2. Exploratory Data Analysis (EDA)
- Visualized class distribution  
- Analyzed feature correlations  
- Used pairplots and boxplots to detect patterns and outliers  

### 3. Model Training
- ✅ Linear SVM (baseline model)  
- ✅ Polynomial Kernel SVM  
- ✅ RBF Kernel SVM  
- ✅ Hyperparameter tuning using GridSearchCV  

### 4. Model Evaluation
- Accuracy  
- Precision, Recall, F1-score  
- Confusion Matrix  
- Decision Boundary Visualization  

---

## 📊 Visualizations
The `visualizations/` folder includes:

- Pairplots showing class separability  
- KDE plots for feature distributions  
- Decision boundary plots  
- Confusion matrix heatmaps  

---

## 🛠️ Technologies Used
- Python  
- Scikit-learn  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Jupyter Notebook  

---

## 📌 Key Insights
- Iris Setosa is the most linearly separable class  
- RBF kernel performs best for non-linear decision boundaries  
- Feature scaling significantly improves SVM performance  

---

## 🚀 Future Improvements
- Feature engineering for better accuracy  
- Compare with other models (Logistic Regression, Decision Trees, Neural Networks)  
- Deploy using Flask or FastAPI  

---

## 🤝 Contributing
Feel free to fork this repository and contribute!

---

## ⭐ Show Your Support
If you like this project, give it a ⭐ on GitHub!
