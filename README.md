🩺 Diabetes Detection Model (For Females)

This project is a machine learning-based system designed to predict whether a female patient is diabetic or not using clinical data. It uses the PIMA Indian Diabetes Dataset and implements a Support Vector Machine (SVM) classifier for prediction.

📌 Project Overview

Diabetes is a common metabolic disorder that can lead to severe health complications if not diagnosed early. This project leverages machine learning to provide a predictive system that can classify individuals as diabetic or non-diabetic based on specific health metrics.

The model focuses on female patients, as it is built using a dataset subset with features relevant to women’s health.

🛠️ Technologies and Libraries Used
Python – Programming language
Pandas & NumPy – Data handling and numerical computation
Scikit-learn (sklearn) – Machine learning algorithms and data preprocessing
StandardScaler – Data standardization
train_test_split – Splitting dataset into training and testing sets
svm.SVC – Support Vector Machine classifier
accuracy_score – Model evaluation metric

📂 Dataset
The project uses the PIMA Indian Diabetes Dataset stored as diabetes.csv.
Key features in the dataset include:
Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age
Target variable (Outcome):
0 → Non-diabetic
1 → Diabetic

⚙️ Project Steps
Data Collection: Load dataset using Pandas.
Exploratory Data Analysis (EDA):
Check dataset shape and statistical summaries.
Analyze target class distribution.
Data Preprocessing:
Separate features (X) and labels (Y).
Standardize features using StandardScaler.
Model Training:
Split data into training (80%) and test (20%) sets.
Train a Support Vector Machine (SVM) classifier with a linear kernel.
Model Evaluation:
Evaluate accuracy on training and test datasets.
Prediction System:
Accept input data for a single patient.
Standardize the input and predict using the trained model.
Output whether the person is diabetic or not.

📈 Model Performance
Training Accuracy: ~
Test Accuracy: ~
📝 How to Run
1.Clone the repository or download the project files.
2.Install required libraries.
3.Run the Jupyter Notebook or Python script.
4.Enter the patient’s data to get a prediction.

🔍 Example Prediction
# Example input for a patient
input_data = (6,148,72,35,0,33.6,0.627,50)

# Output
The person is diabetic

⚡ Future Enhancements
1.Extend the model to include male patients.
2.Use additional machine learning models like Random Forest or XGBoost for improved accuracy.
3.Deploy as a web app for real-time diabetes detection.

