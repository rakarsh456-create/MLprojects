# 🎓 Student Exam Performance Predictor

An end-to-end Machine Learning project that predicts a student’s Maths score based on demographic and academic attributes.

🚀 Live Demo: https://mlprojects-1-2jgz.onrender.com  
💻 GitHub Repo: https://github.com/rakarsh456-create/MLprojects

---

## 📌 Problem Statement

Predict student Maths performance using features like:

- Gender  
- Race/Ethnicity  
- Parental Level of Education  
- Lunch Type  
- Test Preparation Course  
- Reading Score  
- Writing Score  

This helps in understanding how socio-academic factors influence academic performance.

---

## 🧠 ML Workflow

1. Data Ingestion  
2. Data Transformation (Pipeline + ColumnTransformer)  
3. Model Training (Multiple Regressors + Hyperparameter Tuning)  
4. Model Evaluation (R² Score)  
5. Model Serialization using Dill  
6. Deployment with Flask + Gunicorn on Render  

---

## 🏗 Project Architecture

MLprojects/
│
├── notebook/ # EDA and experimentation
│
├── src/
│ ├── components/
│ │ ├── data_ingestion.py
│ │ ├── data_transformation.py
│ │ ├── model_trainer.py
│ │
│ ├── pipeline/
│ │ └── predict_pipeline.py
│ │
│ ├── exception.py
│ ├── logger.py
│ └── utils.py
│
├── templates/ # Frontend HTML files
├── artifacts/ # Saved model & preprocessor
│
├── application.py # Flask App Entry Point
├── requirements.txt
└── setup.py

---

## ⚙️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Flask  
- Gunicorn  
- Render (Cloud Deployment)

---

## 📊 Model Performance

- Best Model Selected using multiple regression algorithms  
- Evaluation Metric: R² Score  
- Achieved strong generalization on test dataset  

---

## 🌐 Deployment

Deployed using:
- Render Web Service
- Gunicorn WSGI server
- Python 3.10 environment

---

## 🎯 Key Highlights

✔ Modular Production-Level ML Architecture  
✔ Reusable Pipelines  
✔ Custom Exception Handling  
✔ Logging System  
✔ End-to-End Deployment  
✔ Clean Frontend UI  

---

## 📌 Future Improvements

- Add Model Monitoring  
- Add Docker Support  
- Add CI/CD Pipeline  
- Add Cloud Storage for artifacts  

---

## 👨‍💻 Author

Built with ❤️ by Akarsh Raj
