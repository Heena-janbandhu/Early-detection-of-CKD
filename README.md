# 🩺 Early Prediction for Chronic Kidney Disease Detection: A Progressive Approach to Health Management

Project descripition : 
Chronic Kidney Disease (CKD) is a major medical problem and can be cured if treated in the early stages. Usually, people are not aware that medical tests we take for different purposes could contain valuable information concerning kidney diseases. Consequently, attributes of various medical tests are investigated to distinguish which attributes may contain helpful information about the disease. The information says that it helps us to measure the severity of the problem, the predicted survival of the patient after the illness, the pattern of the disease and work for curing the disease.

This project is an end-to-end machine learning solution for the early detection of Chronic Kidney Disease (CKD). It includes data analysis, model training, evaluation, and a Flask web application for real-time prediction.

> ✅ This project was developed as part of my internship and focuses on applying data science techniques to real-world healthcare data.

---

## 📌 Project Structure

ckd-early-prediction-main/
├── dataset/
│ └── kidney_disease.csv
├── Training/
│ ├── Chronic_kidney_disease_analysis.ipynb
│ ├── benchmark_models_performance.png
│ ├── ckd.h5
│ └── Flask/
│ ├── CKD.pkl
│ └── scaler.pkl
├── Flask/
│ ├── app.py
│ ├── CKD.pkl
│ ├── scaler.pkl
│ ├── debug_input.csv
│ └── templates/
│ ├── home.html
│ ├── index1.html
│ ├── indexnew.html
│ └── result.html
├── test_ckd.py
├── retrain_model.py
└── debug_model.py


---

## 🔍 Features

- Exploratory Data Analysis and preprocessing
- Model training using various ML algorithms
- Flask-based web app for live predictions
- Model serialization using `pickle` and `h5py`

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, Keras
- Flask
- HTML/CSS (Jinja templates)

---

## 🚀 How to Run Locally

1. Clone the repo:
   
   git clone https://github.com/Heena-janbandhu/Early-detection-of-CKD.git
   cd Early-detection-of-CKD

2. Install dependencies:
   pip install -r requirements.txt

3. Run Flask app:
   cd Flask
   python app.py

4. Visit http://127.0.0.1:5000 in your browser to use the web interface.

🧠 Model Insights
Trained on real-world kidney disease data
Evaluated using accuracy, precision, recall, F1-score
Visual comparison of multiple models

📁 Dataset
The dataset used is available in dataset/kidney_disease.csv.

🙋‍♀️ Author
Heena Janbandhu
🔗 LinkedIn: https://www.linkedin.com/in/heenajanbandhu



