# 🚀 SpaceX Falcon 9 First Stage Landing Prediction

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)
![Google Colab](https://img.shields.io/badge/Colab-Notebook-orange?logo=googlecolab)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML%20Library-yellow?logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

This project is part of the **Digital Empowerment Network – Data Science Internship**.
The goal is to analyze SpaceX launch data and **predict the success of Falcon 9 first stage landings**, which are crucial for rocket reusability and reducing spaceflight costs.

We use **SpaceX REST API**, **Wikipedia scraping**, **Exploratory Data Analysis (EDA)**, and multiple machine learning models to build an accurate prediction system.

---

## 📂 Project Structure

```
├── spacex_falcon9_landing_prediction.ipynb   # Main Colab notebook
├── data/
│   ├── raw/                                  # API + Wikipedia scraped data
│   ├── interim/                              # Cleaned & wrangled data
│   └── processed/                            # Final merged dataset
└── README.md                                 # Project documentation
```

---

## 📊 Exploratory Data Analysis

* Payload mass distribution and landing outcomes.
* Orbit types vs landing success.
* Launch sites and geographical success mapping (Folium).
* Yearly trends showing improved landing success over time.

---

## 🤖 Machine Learning Models

We trained and evaluated the following models:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)

### 🔧 Model Evaluation

| Model                | F1-Score | Accuracy |
| -------------------- | -------- | -------- |
| Logistic Regression  | \~0.89   | \~0.86   |
| Decision Tree        | \~0.91   | \~0.88   |
| Random Forest        | \~0.95   | \~0.90   |
| **SVM (Best Model)** | **0.97** | **0.94** |

✅ **SVM** emerged as the best model for predicting Falcon 9 booster landings.

---

## 📈 Visual Evaluation

* **ROC Curves** and **Precision-Recall Curves** were plotted for Random Forest and SVM to compare model performance.
* Both models performed well, but **SVM showed superior classification ability**.

---

## 📑 Key Insights

* Higher payload mass reduces landing success probability.
* Certain orbits (LEO, GTO) show different success patterns.
* Landing success improved significantly after 2017.
* Predictive modeling can help SpaceX optimize launches and minimize costs.

---

## 📝 Future Work

* Extend dataset with latest SpaceX API data.
* Build an **interactive dashboard** (Plotly Dash or Streamlit).
* Try advanced models like **XGBoost** or **Neural Networks**.
* Deploy the trained model as a **web API** for real-time predictions.

---

## 📚 References

* [SpaceX REST API](https://github.com/r-spacex/SpaceX-API)
* [Wikipedia: Falcon 9 launches](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches)
* [scikit-learn Documentation](https://scikit-learn.org/stable/)

👉 Do you also want me to add a **project screenshot (e.g., Folium map or ROC curve) section** so your repo looks more visual?
