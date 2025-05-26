# ❤️ Heart Disease Prediction using Logistic Regression

A simple machine learning project that uses **Logistic Regression** to predict the presence of heart disease based on health-related features. This project is designed to demonstrate a typical ML workflow: data loading, preprocessing, model training, evaluation, and prediction.

---

## 🧠 Overview

This project uses a classic heart disease dataset (likely from UCI or Kaggle) and applies logistic regression to classify whether a patient has heart disease. It includes:

- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Model training and evaluation
- Model persistence (using pickle or joblib)
- Basic prediction interface (CLI or notebook)

---

## 🔍 Features Used

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate Achieved
- Exercise Induced Angina
- ST Depression
- Number of Major Vessels Colored by Fluoroscopy
- Thalassemia

---

## 📦 Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib / seaborn (for visualization)
- scikit-learn
- pickle or joblib

Install via:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
```

2. Run the script

```bash
python model.py
```

> Optionally use a Jupyter notebook for EDA and visualization

---

## 📊 Model Evaluation

- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- ROC-AUC Score

---

## 🧪 Example Usage

```python
# Load model and make prediction
import pickle
model = pickle.load(open("model.pkl", "rb"))
prediction = model.predict([[63, 1, 3, 145, 233, 1, 0, 150, 0, 2.3, 0, 0, 1]])
print("Prediction:", "Heart Disease" if prediction[0] == 1 else "No Heart Disease")
```

---

## 📂 Project Structure

```
heart-disease-prediction/
├── data/              # Raw dataset
├── model.py           # Core ML logic
├── eda.ipynb          # (Optional) Exploratory analysis
├── model.pkl          # Saved logistic regression model
├── README.md          # Project overview
└── requirements.txt   # Python dependencies
```

---

## 📄 License

This project is licensed under the MIT License.

---

## 🤝 Contributions

Pull requests are welcome! Feel free to fork this project and contribute to it.

---

## 📬 Contact

Created by [Your Name] – feel free to reach out via GitHub or email.
