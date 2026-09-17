# 📊 Customer Churn Prediction Using Artificial Neural Network

## 📌 Project Overview
This project predicts whether a customer is likely to churn using a Deep Learning Artificial Neural Network (ANN).

The project includes data preprocessing, categorical encoding, feature scaling, ANN model development, model training, evaluation, and customer churn prediction.

## 🎯 Objective
The main objective of this project is to build a Deep Learning model that can identify customers who are likely to leave a service.

🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras
- Jupyter Notebook

## 🔄 Project Workflow
1. Load Dataset
2. Data Understanding
3. Data Cleaning
4. Remove Unnecessary Features
5. Categorical Encoding
6. Train-Test Split
7. Feature Scaling
8. Build ANN Model
9. Train the Model
10. Evaluate Model Performance
11. Confusion Matrix
12. Customer Churn Prediction

## 🧠 ANN Architecture
Input Layer
     ↓
Dense Layer – 16 Neurons
     ↓
Dense Layer – 8 Neurons
     ↓
Output Layer – 1 Neuron

Activation Functions

- Hidden Layers: ReLU
- Output Layer: Sigmoid

Optimizer

Adam

Loss Function

Binary Crossentropy

## 📈 Model Evaluation
The model is evaluated using:

- Accuracy
- Loss
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

## 💡 Business Use
Customer churn prediction can help businesses:

- Identify customers at risk of leaving
- Improve customer retention
- Target customers with special offers
- Reduce customer loss
- Improve business decision-making

## 🚀 How to Run
1. Clone the repository

git clone YOUR_GITHUB_REPOSITORY_URL

2. Install dependencies

pip install -r requirements.txt

3. Open Jupyter Notebook

jupyter notebook

4. Open

customer_churn_ann.ipynb

and run the cells.

## 👨‍💻 Project Type
Deep Learning / Machine Learning Project

## 📌 Future Improvements
- Use a larger real-world customer churn dataset
- Hyperparameter tuning
- Add dropout layers
- Compare ANN with Random Forest and XGBoost
- Deploy the model using Streamlit
- Create an interactive churn prediction dashboard
