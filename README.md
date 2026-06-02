# 🏦 Loan Approval Prediction System

A Machine Learning and Deep Learning based Loan Approval Prediction System that uses an Ensemble Model combining Random Forest and Artificial Neural Network (ANN) to predict whether a loan application will be approved.

## 📌 Features

- Loan approval prediction using:
  - Random Forest Classifier
  - Artificial Neural Network (ANN)
  - Ensemble Learning

- Data visualization and analysis
- Interactive user input system
- Credit score eligibility analysis
- Maximum loan amount prediction
- Performance evaluation using:
  - Accuracy Score
  - Classification Report
  - Confusion Matrix

---

## 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- TensorFlow / Keras
- Google Colab

---

## 📊 Dataset Features

The dataset is embedded directly in the code and contains:

| Feature | Description |
|----------|------------|
| Salary | Annual Income |
| Age | Applicant Age |
| CreditScore | Credit Score (300-850) |
| EmploymentStatus | Employment Status (1 = Employed, 0 = Unemployed) |
| LoanAmount | Requested Loan Amount |
| Approved | Loan Approval Status |

---

## 🧠 Model Architecture

### Random Forest

- 100 Estimators
- Max Depth = 5
- Random State = 42

### Artificial Neural Network

Input Layer (5 Features)

Dense Layer (32 neurons, ReLU)

Batch Normalization

Dropout (20%)

Dense Layer (16 neurons, ReLU)

Batch Normalization

Dropout (20%)

Dense Layer (8 neurons, ReLU)

Output Layer (1 neuron, Sigmoid)

---


## 📈 Outputs

The project generates:

- Feature Analysis Graphs
- Class Distribution Pie Charts
- ANN Loss Curve
- ANN Accuracy Curve
- Confusion Matrix
- Loan Approval Prediction
- Minimum Credit Score Analysis
- Maximum Loan Eligibility Analysis

---

## 🎯 Future Improvements

- Real-world banking dataset integration
- Web application using Flask/Django
- REST API deployment
- Explainable AI (SHAP/LIME)
- Model deployment on cloud platforms

---

## 👨‍💻 Author

Pranita Yadav

---

## 📜 License

This project is licensed under the MIT License.
