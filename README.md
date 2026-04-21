# 🩺 Diabetes Detection Model (For Females)

This project is a machine learning-based system designed to predict whether a female patient is diabetic or not using clinical data. It uses the **PIMA Indian Diabetes Dataset** and implements a **Support Vector Machine (SVM)** classifier for prediction.

---

## 📌 Project Overview

Diabetes is a common metabolic disorder that can lead to severe health complications if not diagnosed early. This project leverages machine learning to provide a predictive system that can classify individuals as **diabetic** or **non-diabetic** based on specific health metrics.

The model focuses on **female patients**, as it is built using a dataset subset with features relevant to women’s health.

---

## 🛠️ Technologies and Libraries Used

- **Python** – Programming language  
- **Pandas & NumPy** – Data handling and numerical computation  
- **Scikit-learn (sklearn)** – Machine learning algorithms and preprocessing  
- **StandardScaler** – Data standardization  
- **train_test_split** – Dataset splitting  
- **svm.SVC** – Support Vector Machine classifier  
- **accuracy_score** – Model evaluation  

---

## 📂 Dataset

The project uses the **PIMA Indian Diabetes Dataset** stored as `diabetes.csv`.

### 🔑 Features:
- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  

### 🎯 Target Variable (Outcome):
- `0` → Non-diabetic  
- `1` → Diabetic  

---

## ⚙️ Project Workflow

1. **Load Data**  
   - Use Pandas to load the dataset  

2. **Exploratory Data Analysis (EDA)**  
   - Check shape, statistics, and target distribution  

3. **Data Preprocessing**  
   - Separate features (**X**) and labels (**Y**)  
   - Standardize features using `StandardScaler`  

4. **Model Training**  
   - Split dataset: 80% training, 20% testing  
   - Train SVM with a linear kernel  

5. **Model Evaluation**  
   - Evaluate accuracy on training and testing sets  

6. **Prediction System**  
   - Input single patient data  
   - Standardize input and predict  
   - Output: Diabetic or Not  

---

## 📈 Model Performance

- **Training Accuracy:78.87** ~  
- **Test Accuracy:77.78** ~  

*(Update these values after running your model)*

---

## 📝 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git

