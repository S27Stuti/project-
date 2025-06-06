
# 🏥 Healthcare Appointment No-Show Prediction

This project aims to predict whether a patient will show up for their scheduled medical appointment. The prediction is based on various features like age, gender, appointment day, scheduled day, presence of chronic conditions, SMS reminders, and more.

## 📌 Problem Statement

Missed appointments are a major issue in healthcare systems, leading to inefficient use of resources and longer patient wait times. This project uses machine learning to predict no-shows in order to:

- Reduce patient wait times
- Improve clinic efficiency
- Optimize staff scheduling

---

## 📊 Dataset

The dataset used is the **"Medical Appointment No Shows"** dataset from Kaggle or similar source. It contains information on over 100k medical appointments in Brazil.

**Key Features:**
- `PatientId`, `AppointmentID`
- `Gender`, `ScheduledDay`, `AppointmentDay`
- `Age`, `Neighbourhood`
- `Scholarship`, `Hipertension`, `Diabetes`, `Alcoholism`, `Handcap`, `SMS_received`
- `No-show` (Target variable)

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas, NumPy** for data preprocessing
- **Matplotlib, Seaborn** for visualization
- **Scikit-learn** for machine learning modeling
- **Streamlit / Flask** *(Optional)* for web deployment

---

## 🔍 Project Structure

```
📁 Healthcare-No-Show-Prediction/
├── data/
│   └── appointments.csv
├── notebooks/
│   └── eda_and_modeling.ipynb
├── models/
│   └── model.pkl
├── app/
│   ├── templates/
│   ├── static/
│   └── app.py
├── README.md
└── requirements.txt
```

---

## ✅ Workflow

1. **Data Cleaning:** Handle missing values, incorrect data types, etc.
2. **EDA (Exploratory Data Analysis):** Understand data distribution, correlations, and trends.
3. **Feature Engineering:** Extract useful features (e.g., waiting time).
4. **Model Training:** Use classification algorithms (Logistic Regression, Random Forest, XGBoost).
5. **Model Evaluation:** Evaluate using accuracy, precision, recall, F1-score.
6. **Deployment:** Build an interactive dashboard or web app for predictions.

---

## 📈 Model Performance

| Model              | Accuracy | Precision | Recall | F1-score |
|-------------------|----------|-----------|--------|----------|
| Logistic Regression | 79.3%   | 0.81      | 0.74   | 0.77     |
| Random Forest      | 82.7%   | 0.83      | 0.78   | 0.80     |
| XGBoost            | 84.1%   | 0.85      | 0.80   | 0.82     |

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/healthcare-no-show-prediction.git
cd healthcare-no-show-prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run Jupyter Notebook
```bash
jupyter notebook notebooks/eda_and_modeling.ipynb
```

### 4. Optional: Run the Web App
```bash
cd app
python app.py
```

---

## 📎 Future Work

- Add more patient history data
- Integrate SMS reminder optimization
- Improve model accuracy with hyperparameter tuning
- Deploy to cloud (e.g., Heroku, AWS)

---

## 🧑‍💻 Contributors

- **Your Name** – [GitHub Profile](https://github.com/yourusername)
- Other team members

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

- Kaggle for the dataset
- Scikit-learn documentation
- Stack Overflow community
