# 🌡️ Thermal Comfort Analysis & Prediction (ASHRAE Dataset)

## 📌 Project Overview

This project analyzes human thermal comfort using environmental and personal factors such as temperature, humidity, air velocity, clothing insulation, and metabolic rate.

The goal is to:

* Perform **Exploratory Data Analysis (EDA)**
* Understand relationships between variables
* Build **Machine Learning models** to predict thermal comfort levels

---

## 📊 Dataset

* Source: ASHRAE Thermal Comfort Database
* File used: `ashrae_db2.01.csv`

---

## ⚙️ Features Used

* Air Temperature
* Relative Humidity
* Air Velocity
* Clothing Insulation (Clo)
* Metabolic Rate (Met)

---

## 🧪 Data Processing

* Removed empty columns
* Handled missing values
* Selected relevant features
* Created clean dataset for modeling

---

## 📈 Exploratory Data Analysis

Includes:

* Histograms & Boxplots
* Scatter plots (relationships)
* Correlation heatmap
* PCA visualization
* Interaction analysis (Temperature × Met, Clo, etc.)

---

## 🧠 Machine Learning Models

### 1. Logistic Regression

* Multiclass classification
* Baseline model

### 2. Random Forest

* Improved performance
* Feature importance analysis

### 3. Hyperparameter Tuning

* GridSearchCV used for optimization

---

## 🎯 Target Variable

Thermal sensation converted into:

* Cold ❄️
* Neutral 😐
* Warm 🔥

---

## 📊 Results

* Logistic Regression Accuracy: ~ (fill your result)
* Random Forest Accuracy: ~ (fill your result)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn

---

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
python project.py
```

---

## 📁 Project Structure

```
├── project.py
├── ashrae_db2.01.csv
├── README.md
```

---

## 🚀 Future Improvements

* Add deep learning models
* Deploy as web app
* Real-time prediction system

---

