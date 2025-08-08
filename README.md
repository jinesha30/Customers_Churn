# 📉 Customer Churn Prediction

This project predicts whether a customer will churn (leave) using machine learning. It is built using Python, trained in a Jupyter Notebook, and deployed with a Streamlit web app.

---

## 🚀 How to Run the Project

### 📦 Install Dependencies

Make sure you have Python installed. Then install the required libraries:

pip install pandas scikit-learn streamlit

---

## ▶️ Run the Streamlit App
In your terminal or command prompt, run:

streamlit run app.py

This will open the app in your browser.

## 📊 Dataset

- **File:** `dataset.csv`
- This dataset contains customer details such as:
  - Usage patterns
  - Demographics
  - Subscription information
- The target column is typically named **`Churn`** (indicating whether a customer left or not).

---


## 🧠 Model Info

- The model is trained using the **Jupyter Notebook**: `notebook.ipynb`
- Trained model is saved as: `model.pkl`
- **Libraries used:**
  - `scikit-learn` – for building and training the ML model
  - `pandas` – for data handling
  - `matplotlib` & `seaborn` – for data visualization

---

## 🌐 Streamlit Web App

The web app is built using **Streamlit** to make real-time predictions using the trained model.

### 🔧 Features:
- Simple and interactive user interface
- Allows input of customer attributes
- Predicts **churn probability**
- Displays prediction instantly

---

## 📌 Notes

- Ensure that `model.pkl` is present in the **same directory** as `app.py`.
- If you're using a different filename or directory structure, make sure to **update the paths** inside `app.py`.
