# ❤️ Heart Disease Prediction using Machine Learning

This project predicts the **10-year risk of heart disease** using machine learning models trained on the **Framingham Heart Study dataset**.  
It includes data preprocessing, visualization, model building, evaluation, and prediction using a Jupyter Notebook.

---

## 📁 Project Structure

```
├── Heart disease prediction notebook.ipynb
├── framingham.csv
└── README.md
```

---

## 📌 Overview

Heart disease is a major cause of mortality worldwide.  
Early detection can help reduce complications and improve health outcomes.

This project builds multiple ML models to classify whether a person is at risk of heart disease based on medical and lifestyle factors.

---

## 🧠 Machine Learning Workflow

### **1️⃣ Data Loading**
- Loads `framingham.csv`
- Displays shape, summary, missing values, and column descriptions

### **2️⃣ Data Preprocessing**
- Handles missing data
- Encodes categorical features
- Scales numerical features
- Correlation analysis & feature selection

### **3️⃣ Exploratory Data Analysis (EDA)**
- Histograms and distribution plots
- Correlation heatmap
- Relationship between risk factors and disease

### **4️⃣ Model Training**
Models used:
- Logistic Regression  
- Random Forest  
- KNN  
- Decision Tree  
- SVM  
- Gradient Boosting  

### **5️⃣ Model Evaluation**
Metrics:
- Accuracy  
- Precision, Recall, F1-Score  
- Confusion Matrix  
- ROC Curve / AUC Score  

### **6️⃣ Final Prediction**
Predicts:
- **1 → High risk**  
- **0 → Low risk**

---

## 📊 Dataset Description

Dataset: **Framingham Heart Study**

Key features include:
- Age  
- Sex  
- Blood Pressure  
- Cholesterol Levels  
- Glucose Levels  
- Smoking Habits  
- Diabetes Status  

**Target Column:**  
`TenYearCHD` → 1 (risk), 0 (no risk)

---

## 🛠️ Technologies Used

- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  

---

## 🚀 How to Run the Project

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
```

### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3. Run the Notebook**
```bash
jupyter notebook
```
Open: **Heart disease prediction notebook.ipynb**

---

## 📈 Results

The notebook compares different ML models and identifies the best based on:

- AUC Score  
- F1 Score  
- Accuracy  
- Confusion Matrix  

Visualizations and performance metrics are included in the notebook.

---

## 💡 Key Insights

- Age, cholesterol, blood pressure, and glucose strongly affect heart-disease risk.  
- Smoking and diabetes significantly increase risk.  
- Proper preprocessing improves model accuracy.

---

## 🔮 Future Enhancements

- Hyperparameter tuning (GridSearchCV, RandomSearchCV)  
- Deploy using Flask or Streamlit  
- Interactive UI for predictions  
- Add deep learning models  

---

## 🤝 Contributing

Pull requests are welcome.  
For major changes, open an issue to discuss your idea.

---

## 📝 License

This project is licensed under the **MIT License**.

---

## 📬 Contact

**Your Name**  
GitHub: https://github.com/your-username  
Email: your-email@example.com
