
# Heart Disease Prediction

This is a machine learning project that predicts the presence of heart disease using clinical patient data. The best-performing model was deployed as an interactive web app using Streamlit.

---

##  Project Overview

- **Goal:** Predict heart disease from medical data
- **Models Used:** Logistic Regression, Random Forest, Naive Bayes, SVM, Linear Regression , Decision Tree, KNN
- **Best Model:** Random Forest
- **Deployment:** Streamlit Web App
- **Dataset:** Structured dataset with clinical features such as age, sex, chest pain type, blood pressure, cholesterol, etc.

---

## Project Structure

```
heart-disease-ml-app/
│
├── app.py                    # Streamlit app interface
├── random_forest_model.pkl   # Trained Random Forest model
├── scaler.pkl                # Fitted MinMaxScaler
├── feature_names.pkl         # Feature columns used in training
├── requirements.txt          # Python dependencies
├── final_project1.ipynb      # Full training and evaluation notebook
└── README.md                 # Project documentation (this file)
```

---

##  How to Run the App Locally

1. Clone the repository:
```bash
git clone https://github.com/yourusername/heart-disease-ml-app.git
cd heart-disease-ml-app
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the app:
```bash
streamlit run app.py
```

4. Open browser to [http://localhost:8501](http://localhost:8501)

---

## Model Performance

- **Best Accuracy:**   0.8
- Confusion Matrix, Classification Report, and ROC Curve used for evaluation

---

## Deployment

The model is deployed using [Streamlit Cloud](https://streamlit.io/cloud) and can be accessed through a public URL.

---

## License

This project is for academic purposes.

---
link Git Hub : https://nileuniversity-my.sharepoint.com/:v:/g/personal/s_ebrahim2164_nu_edu_eg/EVGM_5uLcZtMs6nPx97CZEMBGa_2UuQbQ1K1VwBccVS0Vw
## Author

Shahd Ebrahim   
Biotechnology Student – Nile University  

