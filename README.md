# 🧠 Mental Health Score Predictor                                        

A machine learning project that predicts a student's **mental health score** based on their social media usage and lifestyle habits, with a simple web interface for real-time predictions.


[Live](https://mental-health-score-predictor-2fil.onrender.com)

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
| Language   | Python, JavaScript                     |
| ML / Data  | Pandas, NumPy, Scikit-learn, Matplotlib|
| Backend    | [Flask / FastAPI]                      |
| Frontend   | HTML, CSS, JavaScript                  |
| Notebook   | Jupyter Notebook                       |

---

## 📂 Project Structure
Mental-Health-Score_Predictor/
│
├── main.py # Backend app / prediction API
├── Mental_Health_Model.pkl # Trained ML model
├── ML_Project.ipynb # Data analysis & model training notebook
├── ML Project.html # Exported notebook (HTML view)
├── Student Social Media And Mental Health Impact.csv # Dataset
├── index.html # Frontend page
├── style.css # Styling
├── script.js # Frontend logic
├── requirements.txt # Python dependencies
└── README.md


---

## 📊 Dataset

- **Name:** Student Social Media And Mental Health Impact
- **Contains:** [e.g., daily social media hours, sleep hours, platform used, age, academic level, mental health score]
- **Target Variable:** Mental Health Score

---

## 🔄 Workflow

1. Load and clean the dataset
2. Exploratory Data Analysis (EDA)
3. Feature encoding and scaling
4. Train-test split
5. Model training and evaluation
6. Save the best model using `pickle` / `joblib`
7. Integrate the model with the web app

---

## 📈 Model Performance

| Metric   | Score   |
|----------|---------|
| R² Score | [value] |
| MAE      | [value] |
| RMSE     | [value] |

**Final Model:** [e.g., Random Forest Regressor]

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
python main.py
```

**5. Open in browser**


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
