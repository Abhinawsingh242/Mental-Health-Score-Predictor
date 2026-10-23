# 🧠 Mental Health Score Predictor  [Live](https://mental-health-score-predictor-2fil.onrender.com)                                      

A machine learning project that predicts a student's **mental health score** based on their social media usage and lifestyle habits, with a simple web interface for real-time predictions.

### Screenshots

<img width="2940" height="1456" alt="AF8E1B10-E139-4499-8990-66D61369593F_1_201_a" src="https://github.com/user-attachments/assets/516ad48e-235f-46fc-919d-53a8800159f1" />
<img width="2940" height="1478" alt="2DA613DC-5965-4B19-91C2-5BCAF52AC553_1_201_a" src="https://github.com/user-attachments/assets/1937a145-6238-4fd6-b574-13994f079ad8" />

---

## 📌 Overview

Excessive social media use is increasingly linked to students' well-being. This project analyzes that relationship and builds a trained ML model that estimates a mental health score from user inputs such as usage time, sleep, and related factors.

---

## ✨ Features

- Data cleaning, EDA, and visualization of the student dataset
- Trained regression model saved as a `.pkl` file
- Python backend (`main.py`) serving predictions
- Clean frontend (HTML, CSS, JavaScript) for user input and results
- Easy setup using `requirements.txt`

---

## 🛠️ Tech Stack

| Category   | Tools                                  |
|------------|----------------------------------------|
| Backend    | [FastAPI, Pydantic]                      |
| Frontend   | HTML, CSS, JavaScript                  |
| Machine Learning  | scikit-learn                  |
| Data Processing   | Pandas, Numpy                  |
| Visualization  | Matplotlib  |
| Model Persistence   | Joblib                     |

---

Mental-Health-Score_Predictor/
├── main.py
├── Mental_Health_Model.pkl
├── ML_Project.ipynb
├── ML Project.html
├── Student Social Media And Mental Health Impact.csv
├── index.html
├── style.css
├── script.js
├── requirements.txt
└── README.md

---

## 📊 Dataset

- **Dataset:** Student Social Media and Mental Health Impact
- **Dataset Size:** 5,000 student records and 13 columns, as documented in the notebook
- **Input Features:** Demographics, social media usage, study hours, sleep duration, physical activity, and stress level
- **Target Variable:** `Mental_Health_Score`
- **Problem Type:** Supervised Learning — Regression

The model estimates a mental health score using student lifestyle and social media usage features.

**Disclaimer:** The predicted score is intended for educational purposes only and must not be interpreted as a clinical assessment or medical diagnosis.

---

## 🔄 Workflow

1. Load and clean the dataset
2. Exploratory Data Analysis (EDA)
3. Feature encoding and scaling
4. Train-test split
5. Model training and evaluation
6. Save the selected preprocessing and Random Forest pipeline using Joblib.
7. Integrate the model with the web app

---

## 📈 Model Performance

Three regression models were evaluated on the test set.

| Model | R² Score | MAE | RMSE |
|---|---:|---:|---:|
| Linear Regression | 0.7398 | 0.5362 | 0.6760 |
| Random Forest (Default) | 0.8776 | 0.3472 | 0.4637 |
| Random Forest (Tuned) | 0.8650 | 0.3689 | 0.4869 |

**Model used by the application:** Random Forest Regressor (default configuration), subject to verification against the deployed model file.

The default Random Forest achieved an R² score of approximately 0.878 on the recorded test set.

*These metrics reflect performance on the evaluated dataset. They do not establish clinical validity or guarantee accurate predictions for individual students.*
---

## 🚀 Installation & Setup

**1. Clone the repository**
```bash
git clone https://github.com/Abhinawsingh242/Mental-Health-Score_Predictor.git
cd Mental-Health-Score_Predictor
```

**2. Create a virtual environment (recommended)**
```bash
python -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Run the application**

```bash
uvicorn main:app --reload
```

**5. Open the application**

- Local application: http://127.0.0.1:8000/
- Interactive API documentation: http://127.0.0.1:8000/docs

---

## 💻 Usage

1. Open the web app in your browser
2. Enter the required details (social media hours, sleep, etc.)
3. Click **Predict**
4. View your predicted mental health score

---

## ⚠️ Disclaimer

This project is built for **educational purposes only**. The predictions are not a medical diagnosis. For any mental health concerns, please consult a qualified professional.

---

## 🔮 Future Improvements

- Add more features and a larger dataset
- Try advanced models and hyperparameter tuning
- Add visual charts in the result section

---

## 🤝 Contributing

Contributions are welcome! Fork the repo, create a new branch, and open a pull request.

---

## 👨‍💻 Author

**Abhinaw Singh**
GitHub: [@Abhinawsingh242](https://github.com/Abhinawsingh242)

---
