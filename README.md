This project demonstrates a **real-world healthcare machine learning workflow** focused on **cardiovascular disease prediction**, one of the leading causes of death globally.

✔ Medical domain relevance  
✔ Clean end-to-end ML pipeline  
✔ Strong EDA + statistical insights  
✔ Interpretable Logistic Regression model  
✔ Resume & portfolio optimized  

---

## 📌 Problem Statement
Heart disease is a major global health issue. Early detection can significantly reduce mortality rates and healthcare costs.

> **Goal:** Predict whether a patient has heart disease using clinical and demographic attributes.

---

## 🧠 Solution Overview
This project builds a supervised ML system that:
- Analyzes patient medical records
- Identifies high-risk indicators for heart disease
- Predicts disease presence with measurable accuracy
- Supports data-driven clinical decision-making

---

## 🗂 Dataset Information
- **Dataset:** Heart Disease Dataset (UCI / Kaggle)
- **Type:** Structured clinical data
- **Target Variable:** `target`
  - `0` → No Heart Disease
  - `1` → Heart Disease Present

### 🔑 Features
| Feature | Description |
|------|------------|
| age | Age of patient |
| sex | Gender |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol |
| fbs | Fasting blood sugar |
| restecg | Resting ECG |
| thalach | Maximum heart rate |
| exang | Exercise induced angina |
| oldpeak | ST depression |
| slope | ST slope |
| ca | Major vessels |
| thal | Thalassemia type |

---

## 🔬 Exploratory Data Analysis (EDA)
Key analysis performed:
- Distribution of heart disease cases
- Gender-wise & age-wise risk analysis
- Chest pain vs heart disease relationship
- Correlation heatmap for feature importance

> EDA reveals critical clinical patterns influencing heart disease risk.

---

## 🛠 Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Train-test split

---

## 🤖 Machine Learning Model
### Logistic Regression
Chosen for:
- High interpretability (medical use-case)
- Fast training
- Strong baseline performance

### 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📈 Results & Key Insights
- Model shows strong predictive capability
- Chest pain type, max heart rate, and age are major predictors
- Results align with real cardiology research findings

---

## 🧪 Project Workflow
```
Data Collection
      ↓
Exploratory Data Analysis
      ↓
Preprocessing
      ↓
Model Training
      ↓
Evaluation
      ↓
Clinical Insights
```

---

## ⚙️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **IDE:** Jupyter Notebook

---

## ▶️ How to Run the Project
```bash
git clone https://github.com/UmairImtiaz658/heart-disease-prediction-ml.git
cd heart-disease-prediction-ml
jupyter notebook Heart_disease_pred_using_LR.ipynb
```

---

## 🏥 Real-World Applications
- Cardiac risk screening
- Preventive healthcare analytics
- Clinical decision support systems
- Medical research

---

## 🔮 Future Improvements
- Hyperparameter tuning
- Advanced models (Random Forest, XGBoost)
- Model deployment (Streamlit / Flask)
- Integration with hospital systems

---

## 👨‍💻 Author
**Umair Imtiaz**  
Data Scientist  # Heart-Disease-Prediction-using-Linear-Regression
