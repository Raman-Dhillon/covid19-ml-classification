# 🦠 COVID-19 Detection Using Machine Learning
## 📌 Project Overview

This repository presents an end-to-end COVID-19 prediction system developed using machine learning techniques. The project focuses on accurately classifying COVID-19 cases using medical data by performing data preprocessing, model training, validation, and performance evaluation. The notebook is optimized for clean, reproducible, and GitHub-ready output following modern ML best practices.

## 🎯 Objectives

1. Build an efficient ML/DL model for COVID-19 detection

2. Demonstrate the application of AI in healthcare
3. Achieve high classification accuracy with reliable evaluation

4. Maintain clean and reproducible experimentation suitable for GitHub

## 🧠 Methodology

1. Data loading and preprocessing

2. Feature extraction and normalization

3. Model building using deep learning

4. Training and validation
5. Model evaluation using standard metrics
## ⚙️Technologies Used

1. Python

2. TensorFlow / Keras

3. NumPy

4. Pandas

5. Matplotlib 

6. Scikit-learn
## 📊 Dataset

1. Publicly available COVID-19 medical dataset

2. Data is cleaned, normalized, and split into training and validation sets
3. Dataset imbalance is handled during evaluation
## 📈 Evaluation Metrics
1. Accuracy
2. Precision
3. Recall
4. F1-Score
5. Confusion Matrix
##  📊 Model-wise Results
### Custom CNN
![covid19-ml-classification](\covidcnnconfusionmatrix.png)

##  📈 Performance Comparision
| Model        | Train Accuracy | Validation Accuracy |
|--------------|----------------|---------------------|
| Custom CNN   | 0.3450       | 0.9883                 |
| ResNet50    | 0.9876         | 0.9993                |
| Inception v3| 0.8719        | 0.9652              |

## 🚀 Results
The trained model achieves high prediction accuracy, demonstrating its effectiveness in distinguishing COVID-19 cases. The results indicate that machine learning can significantly support automated and rapid medical diagnosis.
## 🧹 Clean Notebook Practices
1. Modern .keras model saving format
2. Suppressed non-critical warnings
3. Optimized TensorFlow logging
4. Clean output cells for GitHub presentation
##  🔮 Future Enhancements
1. Multi-class classification (COVID-19 / Pneumonia / Normal)
2. Deployment as a web or mobile application
3. Training on larger and more diverse datasets
4. Integration with real-time medical systems
## ▶️ How to Run
pip install -r requirements.txt

**Open the notebook:**

COVID_19_Prediction.ipynb

