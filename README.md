# 🎓 Student Exam Performance Predictor

A machine learning web application built with Flask to predict a student's **Math score** based on demographic and academic-related inputs like gender, ethnicity, reading and writing scores, parental education, and more.

---

## 📌 Project Overview

This project uses a **Decision Tree Regressor** model trained on educational performance data to predict math scores. The application features a simple yet elegant web interface built with **Flask** and **Bootstrap**, enhanced with:

- Dark theme UI
- Bright yellow text styling
- Centered, responsive layout
- Logo and spinner animation

---

## 🚀 Features

- Predict math score using user inputs via a form
- Preprocessing pipeline for data transformation
- Model training and evaluation
- Flask backend for API handling
- Streamlined frontend with a responsive and styled interface

---

## 🧠 Technologies Used

| Component | Technology |
|----------|------------|
| Backend | Flask, Python |
| ML Model | Scikit-learn (DecisionTreeRegressor) |
| Frontend | HTML, Bootstrap 5, CSS |
| Logging | Python logging module |
| Packaging | Custom `setup.py`, `requirements.txt` |
| Utilities | NumPy, Pandas, Joblib, Pickle |

---

## 📁 Project Structure

```
ml_project/
│
├── static/                  # Logo and assets
│   └── logo.png
├── templates/
│   └── home.html            # Web form and UI
├── src/
│   ├── components/          # Data transformation & model trainer
│   ├── exception.py         # Custom error handling
│   ├── logger.py            # Logging configuration
│   ├── pipeline/
│   │   └── predict_pipeline.py  # Prediction logic
│   └── utils.py             # Utility functions
├── app.py                   # Flask app
├── setup.py                 # Python package config
├── requirements.txt
└── README.md
```

---

## ⚙️ How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/ml_project.git
cd ml_project
```

### 2. Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Flask App
```bash
python app.py
```

Visit `http://127.0.0.1:5000/` in your browser.

---

## 🧪 Model & Evaluation

- Model used: `DecisionTreeRegressor`
- Evaluation metric: `Mean Absolute Error (MAE)`
- Hyperparameter tuning: max_leaf_nodes evaluated over multiple values

---

## 📷 Screenshots

> Add screenshots of your app here (UI form, prediction results, etc.)

---

## 🧾 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- Dataset inspiration: [Kaggle Student Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- Scikit-learn and Flask documentation