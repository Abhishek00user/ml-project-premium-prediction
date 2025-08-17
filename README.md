---

# 🏥 Health Insurance Cost Predictor

This project is a **Machine Learning Web Application** that predicts the **Health Insurance Premium Cost** of an individual based on various personal and lifestyle factors.

The app is built using **Logistic Regression** and deployed with **Streamlit** for interactive use.

🔗 **Live Demo**: [Health Insurance Cost Predictor](https://ml-project-premium-prediction-tf7.streamlit.app)

---

## 📸 Screenshot

![App Screenshot](./Screenshot (2).png)

---

## 🚀 Features

* Predicts health insurance premium cost based on user inputs.
* User-friendly web interface built with **Streamlit**.
* Considers multiple input factors like:

  * Age
  * Number of Dependents
  * Income
  * Genetical Risk
  * Insurance Plan (Bronze, Silver, Gold, etc.)
  * Employment Status
  * Gender
  * Marital Status
  * BMI Category
  * Smoking Status
  * Region
  * Medical History

---

## 🧠 Machine Learning Model

* **Algorithm Used**: Logistic Regression
* **Steps Involved**:

  1. Data preprocessing (handling categorical & numerical features).
  2. Feature encoding and normalization.
  3. Training Logistic Regression model on historical health insurance data.
  4. Model evaluation and tuning.
  5. Deployment on Streamlit for real-time predictions.

---

## 🖥️ Tech Stack

* **Python**
* **Pandas, NumPy, Scikit-learn** (for ML & preprocessing)
* **Streamlit** (for deployment & UI)

---

## 📂 Project Structure

```
📦 Health-Insurance-Cost-Predictor
│── artifacts/                     # trained model files
│── main.py                    # Streamlit application
│── prediction_helper.py       # helper
│── requirements.txt          # Dependencies
│── screenshot.png            # App screenshot
│── README.md                 # Project documentation
```

---

## ⚡ Installation & Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/health-insurance-cost-predictor.git
   cd health-insurance-cost-predictor
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

4. Open the app in your browser at `http://localhost:8501/`.

---

## 📊 Example Prediction

For inputs like:

* Age: 18
* Dependents: 0
* Income: 0
* Insurance Plan: Bronze
* Employment: Salaried
* Smoking Status: No Smoking

👉 The app predicts a **Health Insurance Cost of 4004**.

---

## 📌 Future Improvements

* Improve model accuracy with advanced algorithms (Random Forest, XGBoost, Neural Networks).
* Include additional health-related features.
* Deploy on cloud platforms with authentication.

---

