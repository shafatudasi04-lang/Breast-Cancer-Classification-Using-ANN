Breast Cancer Classification Using ANN 🧠
📌 Project Overview

This project uses an Artificial Neural Network (ANN) to classify breast cancer tumors as Benign or Malignant.

The model is built using Deep Learning techniques and achieved excellent performance on the test dataset.

🎯 Project Objective

The main objective of this project is to develop an ANN model that can predict whether a breast tumor is:

🟢 Benign (Non-Cancerous)
🔴 Malignant (Cancerous)
📊 Dataset Information
Information	Details
Dataset	Breast Cancer Dataset
Total Records	569
Total Features	30
Target Column	diagnosis
Problem Type	Binary Classification
Dataset Classes
Class	Encoded Value
Benign (B)	0
Malignant (M)	1
⚙️ Technologies Used
Python 🐍
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
TensorFlow
Keras
Kaggle
🔄 Project Workflow
Load Dataset
     ↓
Data Understanding
     ↓
Data Preprocessing
     ↓
Remove ID Column
     ↓
Encode Diagnosis Labels
     ↓
Train-Test Split
     ↓
Feature Scaling
     ↓
Build ANN Model
     ↓
Train Model
     ↓
Model Evaluation
     ↓
Classification Report
     ↓
Confusion Matrix
🧹 Data Preprocessing

The following preprocessing steps were performed:

Loaded the dataset using Pandas
Checked dataset structure
Removed the id column
Separated input features and target variable
Encoded diagnosis labels
Split data into training and testing sets
Applied StandardScaler
🧠 ANN Model Architecture
Input Layer (30 Features)
        ↓
Dense Layer (64 Neurons, ReLU)
        ↓
Dense Layer (32 Neurons, ReLU)
        ↓
Dropout Layer (0.2)
        ↓
Dense Layer (16 Neurons, ReLU)
        ↓
Output Layer (1 Neuron, Sigmoid)
⚙️ Model Configuration
Parameter	Value
Optimizer	Adam
Loss Function	Binary Crossentropy
Activation Function	ReLU
Output Activation	Sigmoid
Epochs	50
Batch Size	16
📂 Dataset Split
Dataset	Samples
Training Data	455
Testing Data	114
Total	569
📈 Model Performance
Validation Results
Metric	Result
Validation Accuracy	95.60%
Validation Loss	0.137
Final Test Results
Metric	Result
Test Accuracy	🏆 98.25%
Test Loss	0.1527
Correct Predictions	112 / 114
📊 Confusion Matrix
                 Predicted
                 Benign  Malignant

Actual Benign      72        0
Actual Malignant    2       40
Interpretation
✅ 72 Benign cases correctly predicted
✅ 40 Malignant cases correctly predicted
❌ 2 Malignant cases predicted incorrectly
🎯 Total correct predictions: 112 out of 114
📋 Classification Metrics

The model was evaluated using:

Accuracy Score
Classification Report
Precision
Recall
F1-Score
Confusion Matrix
🚀 Installation

Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
▶️ How to Run
Clone or download this repository.
Open the Jupyter Notebook or Kaggle Notebook.
Install the required libraries.
Add the Breast Cancer dataset.
Run all cells sequentially.
Train the ANN model.
Evaluate the final results.
📁 Project Structure
Breast-Cancer-Classification-Using-ANN/
│
├── breast-cancer.csv
├── ANN_Breast_Cancer.ipynb
├── README.md
└── ANN_Breast_Cancer_Project_Documentation.pdf
🔮 Future Improvements
Add Early Stopping
Perform Hyperparameter Tuning
Compare ANN with other Machine Learning models
Try Random Forest
Try XGBoost
Try Support Vector Machine (SVM)
Perform Cross Validation
Deploy the model as a web application
👨‍💻 Author

Shafaat Ullah

AI & Data Science Student

⚠️ Disclaimer

This project is created for educational and research purposes only. It should not be used as a replacement for professional medical diagnosis.

⭐ Support

If you like this project, please consider giving it a ⭐ star on GitHub!
