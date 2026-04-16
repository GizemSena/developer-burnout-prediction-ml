# 🔥 Developer Burnout Prediction (Data Analysis & Machine Learning)

## 📌 Project Overview

This project focuses on analyzing and predicting **developer burnout levels** using a dataset of 7000 samples.
The goal is to uncover key factors affecting burnout and build a machine learning model to classify burnout levels.

---

## 📊 Dataset Information

The dataset contains the following features:

| Feature          | Description                         |
| ---------------- | ----------------------------------- |
| age              | Age of the developer                |
| experience_years | Years of experience                 |
| daily_work_hours | Daily working hours                 |
| sleep_hours      | Average sleep duration              |
| caffeine_intake  | Daily caffeine consumption          |
| bugs_per_day     | Bugs handled per day                |
| commits_per_day  | Code commits per day                |
| meetings_per_day | Number of meetings                  |
| screen_time      | Daily screen time                   |
| exercise_hours   | Physical activity duration          |
| stress_level     | Stress level indicator              |
| burnout_level    | Target variable (Low, Medium, High) |

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔍 Exploratory Data Analysis (EDA)

The following visualizations were used:

* 📌 Correlation Heatmap
* 📌 Feature Distribution Histograms
* 📌 Burnout vs Stress Level (Boxplot)
* 📌 Burnout vs Sleep Hours
* 📌 Stress vs Sleep (Scatter Plot)
* 📌 Feature Importance

---

## 🤖 Machine Learning Model

* Model Used: **Random Forest Classifier**
* Data Split: 80% Training / 20% Testing
* Preprocessing:

  * Missing values handled
  * Label Encoding applied
  * Feature Scaling (StandardScaler)

---

## 📈 Results

The model successfully predicts burnout levels based on behavioral and lifestyle features.

### Evaluation Metrics:

* Classification Report (Precision, Recall, F1-score)
* Confusion Matrix

---

## 🔥 Key Insights

* Higher **stress levels** significantly increase burnout risk
* Lower **sleep hours** are strongly associated with burnout
* Longer **working hours** lead to higher burnout probability
* Regular **exercise** helps reduce burnout
* Increased **screen time** and **meetings** contribute to fatigue

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/burnout-prediction.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook:

```bash
jupyter notebook
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## ⭐ Acknowledgements

This project is created for learning and data analysis practice.

---
