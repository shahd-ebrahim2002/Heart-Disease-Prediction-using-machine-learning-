
# Heart Disease Prediction - Machine Learning Project

This project applies various machine learning models to predict the presence of heart disease using a patient medical dataset. The best-performing model is deployed using Streamlit for user interaction.

---
 Project Structure

```
heart-disease-ml/
│
├── app.py                       # Streamlit web app
├── random_forest_model.pkl     # Trained best model
├── scaler.pkl                  # Preprocessing scaler 
├── requirements.txt            # Python dependencies
├── final project1.ipynb        # Complete notebook with all ML steps
└── Heart_Disease_ML_Report.docx  # Final report with figures
```

---

 How to Run the App Locally

1. Clone the repository or download the files
2. Open Anaconda Prompt or terminal
3. Navigate to the project folder
4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Run the Streamlit app:

```bash
streamlit run app.py
```

---

Models Used

- Logistic Regression
- Random Forest (Best)
- Naive Bayes
- Support Vector Machine
- XGBoost
- Linear Regression (as classifier if assumptions met)

---

Deployment

The app is deployed using Streamlit Cloud and can be accessed via the provided public link.

---

Performance

- Best Model: **Random Forest**
- Accuracy: *[Add your best accuracy here]*
- Evaluation metrics include: confusion matrix, classification report, and ROC curve.

---

 Dataset

The dataset used contains various clinical features such as:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol
- Blood sugar, ECG results, and more...

---

Author

Shahd Ebrahim  
Biotech senior | Machine Learning Enthusiast


