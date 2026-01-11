# ✈️ Airline Customer Satisfaction – Machine Learning Project

![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Classification-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Project Overview

This project focuses on **predicting airline customer satisfaction** using advanced **Machine Learning** techniques. The goal is to analyze passenger experience data, identify key factors influencing satisfaction, and build robust predictive models.

The project combines:

* 📊 **Data Visualization & EDA**
* ⚙️ **Feature Engineering & SMOTE balancing**
* 🤖 **Multiple ML models**
* 📈 **Model evaluation & comparison**
* 🔍 **Explainable AI (SHAP & LIME)**

---

## 📂 Dataset

* **Source:** Airline Passenger Satisfaction Dataset
* **Size:** ~100k+ records
* **Target Variable:** `satisfaction` (Satisfied / Neutral or Dissatisfied)

### Key Features:

* Demographics: Age, Gender, Customer Type
* Travel Info: Class, Type of Travel, Flight Distance
* Services: Inflight WiFi, Seat Comfort, Online Boarding, Cleanliness
* Delays: Departure & Arrival Delay

---

## 🔎 Exploratory Data Analysis (EDA)

### 📊 Visualizations Included

| Visualization  | Description                            |
| -------------- | -------------------------------------- |
| **Bar Chart**  | Distribution of satisfaction classes   |
| **Line Chart** | Trends across service ratings          |
| **Heatmap**    | Correlation between numerical features |
| **Boxplots**   | Outlier detection & removal            |

📁 All visuals are stored in the `images/` folder and embedded in this README.

---

## 🧹 Data Preprocessing

* Missing value handling
* Label Encoding (categorical features)
* Outlier removal using **IQR method**
* Feature scaling using **StandardScaler**
* Class imbalance handled using **SMOTE**

---

## 🤖 Machine Learning Models

### 1️⃣ Logistic Regression

* Baseline & scaled versions
* Cross-validation applied
* **Test Accuracy:** ~87.5%

### 2️⃣ Random Forest Classifier

* Baseline & class-weighted versions
* Excellent generalization
* **Test Accuracy:** ~95.2%
* **AUC:** ~0.99

### 3️⃣ XGBoost Classifier

* Best performing model
* Hyperparameter tuning & CV
* **Test Accuracy:** ~96.1%
* **AUC:** ~0.99+

---

## 📈 Model Comparison

| Model               | Accuracy  | AUC       | Remarks              |
| ------------------- | --------- | --------- | -------------------- |
| Logistic Regression | ~0.88     | 0.93      | Fast & interpretable |
| Random Forest       | ~0.95     | 0.99      | Strong performance   |
| XGBoost             | **~0.96** | **0.99+** | ⭐ Best model         |

---

## 🧠 Explainable AI (XAI)

To ensure transparency and trust:

### 🔍 SHAP

* Global & local feature importance
* Visual explanation of predictions

### 🧩 LIME

* Instance-level explanation
* Why a passenger is predicted satisfied/dissatisfied

These insights help airlines make **data-driven decisions**.

---

## 🖼️ Sample Visual Outputs

```text
images/
 ├── bar_chart.png
 ├── line_chart.png
 ├── heatmap.png
 ├── accuracy_plot.png
 └── model_comparison.png
```

---

## 🛠️ Tech Stack

* **Python**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**
* **Scikit-learn**
* **XGBoost**
* **SHAP, LIME**
* **Google Colab**

---

##  How to Run

```bash
git clone https://github.com/your-username/airline-customer-satisfaction-ml.git
cd airline-customer-satisfaction-ml
pip install -r requirements.txt
```

Run the notebook in **Google Colab** or Jupyter Notebook.

---

## 👩‍💻 Author

**Anisha Maroof**
 LinkedIn: *www.linkedin.com/in/anisha-maroof-9a85303a3


 GitHub: anishamaroof

---

⭐ *If you find this project useful, don’t forget to star the repository!*

