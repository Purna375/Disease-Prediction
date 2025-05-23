# 🩺 Disease Prediction Using Machine Learning

A machine learning-based health prediction system that analyzes user symptoms to predict possible diseases using models like SVM, Naive Bayes, and Random Forest. The system leverages ensemble techniques to improve prediction accuracy.

---

## 📌 Features

- Accepts user symptoms as input.
- Predicts the likelihood of diseases using multiple ML classifiers.
- Uses an ensemble (mode voting) technique for final prediction.
- Visual performance metrics and comparison across models.
- Provides health recommendations based on predictions.

---

## 🧠 Flowcharts

### 📊 Workflow Overview

![Workflow](./flow%20chart.jpg)

### 🔍 Prediction System Flow

![System Architecture](./DiseasePrediction%20flow.png)

---

## ⚙️ Technologies Used

- **Python** – Core programming language
- **Pandas & NumPy** – Data manipulation and preprocessing
- **Scikit-learn** – Machine learning models and evaluation
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Development environment

---

## 🚀 How to Run the Project

### 🔧 Prerequisites

Ensure you have the following installed:
- Python 3.8+
- pip

### 📥 Installation

```bash
git clone https://github.com/yourusername/disease-prediction-ml.git
cd disease-prediction-ml
pip install -r requirements.txt
```

### 🧪 Run the Notebook

```bash
jupyter notebook Notebook-Disease_Prediction_Using_Machine_Learning.ipynb
```
## 🧬 Dataset
- **Dataset used:** [`data.csv`](./data.csv)
- Contains symptoms as input features and target disease labels.

## 📈 Results
- Achieved high accuracy across models using cross-validation.
- Final prediction is based on **mode voting** from:
  - Support Vector Machine (SVM)
  - Naive Bayes
  - Random Forest
- Visualized metrics (accuracy, precision, recall, F1) to evaluate models.

## 🤝 Contributing
We welcome contributions!  
Please **fork the repository**, create a new branch, and submit a **pull request** for any enhancements or bug fixes.

## 📄 License
This project is licensed under the **MIT License**.  
See the [`LICENSE`](./LICENSE) file for details.

## ✨ Acknowledgments
- Thanks to the open-source ML libraries powering this project:
  - [Scikit-learn](https://scikit-learn.org/)
  - [Pandas](https://pandas.pydata.org/)
  - [Matplotlib](https://matplotlib.org/)
- Thanks to medical open datasets for enabling research.

---

### ✅ Next Steps
- ✅ Replace `https://github.com/Purna375/Disease-Prediction.git` with your actual repo link.
- ✅ Ensure the image files are properly named and placed.
- 🚀 Optional: Add badge icons (e.g., MIT license, last updated, Python version) for a polished look.
