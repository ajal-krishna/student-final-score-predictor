# 🎓 Student Final Score Predictor using Machine Learning

A **supervised machine learning regression project** that predicts a student’s **final exam score** based on academic and behavioral performance indicators.
This project is designed for **educational use**, **college submission**, and **beginner ML portfolios**.

---

## 📌 Project Overview

Educational institutions often struggle to identify students who may underperform in final exams.
This project uses **Linear Regression** to predict final exam marks early, helping teachers and students take corrective actions.

The model learns relationships between attendance, internal assessments, assignments, and daily study habits to estimate the final score.

---

## ✨ Key Features

* Predicts **Final Exam Marks (out of 100)**
* Input features:

  * Attendance percentage
  * Internal Test 1 score (out of 40)
  * Internal Test 2 score (out of 40)
  * Assignment score (out of 10)
  * Daily study hours
* Uses **Linear Regression** for simplicity and interpretability
* Includes:

  * Exploratory Data Analysis (EDA)
  * Correlation heatmap
  * Feature scaling using StandardScaler
  * Train–test split
  * Model evaluation metrics
  * Visualization of predictions
  * Interactive prediction UI using **ipywidgets**
* Fully reproducible with a fixed random state

---

## 🛠️ Tech Stack

* **Programming Language**: Python 3
* **Libraries Used**:

  * pandas, numpy
  * scikit-learn
  * matplotlib, seaborn
  * ipywidgets
* **Development Environment**: Google Colab

---

## 📊 Dataset Description

* **File Name**: `Final_Marks_Data (1).csv`
* **Total Records**: ~3000 students
* **Features**:

  * Attendance (%)
  * Internal Test 1 (0–40)
  * Internal Test 2 (0–40)
  * Assignment Score (0–10)
  * Daily Study Hours
* **Target Variable**:

  * Final Exam Marks (0–100)

---

## 🚀 How to Run the Project

### Option 1: Run in Google Colab (Recommended)

1. Open the notebook in Google Colab
   

   ```
 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/ajal-krishna/student-final-score-predictor/blob/main/student_score_predictor.ipynb)


   ```

2. Upload the dataset file `Final_Marks_Data (1).csv`

3. Run all cells sequentially

4. Use the **interactive sliders** at the bottom of the notebook to predict student scores

---

## 📈 Model Performance (Linear Regression)

| Metric   | Value (Approx.) |
| -------- | --------------- |
| MAE      | 5 – 7 marks     |
| RMSE     | 6 – 9 marks     |
| R² Score | 0.80 – 0.87     |

The results show a **strong linear relationship** between the selected features and final exam performance.

---

## 📁 Project Structure

```
student-final-score-predictor/
│
├── Student_Final_Score_Predictor.ipynb
├── Final_Marks_Data (1).csv
├── README.md
└── images/ (optional – plots/screenshots)
```

---

## 🎯 Use Cases

* Early identification of students at academic risk
* Supporting teachers with data-driven insights
* Demonstrating regression concepts for:

  * College projects
  * ML labs
  * Viva and interviews

---

## 🔮 Future Enhancements

* Try advanced regression models (Random Forest, XGBoost)
* Convert the notebook into a web app using Streamlit or Gradio
* Add pass/fail classification
* Include feature importance analysis

---

## 📄 License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute it for educational purposes.

---

## 👨‍💻 Author

**Ajal Krishna**
B.Tech Computer Science Engineering
Beginner Machine Learning Enthusiast 🚀

---

⭐ If you like this project, don’t forget to star the repository!
