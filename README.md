# 📊 Student Performance Predictor for EduQuest Coaching

This project is developed as part of an **internship at YBI Foundation**. The goal is to build a machine learning system that can analyze and predict student performance based on multiple academic and behavioral features.

---

## 🧠 Objective

To predict the **final exam score** of students using past academic performance, attendance, participation, and demographic data. Additionally, the project classifies students into performance categories to identify those who may require additional support.

---

## 📁 Dataset

The dataset contains features such as:

* Attendance rate
* Previous exam score
* Class participation score
* Learning hours per week
* Parental education
* And more...

---

## 🔍 Key Steps

### 1. Data Preprocessing

* Label encoding for categorical variables
* Standardization of numeric features

### 2. Exploratory Data Analysis (EDA)

* Histogram, boxplot, scatterplot, pairplot
* Correlation heatmap to identify important features

### 3. Regression Models Compared

* Linear Regression
* Random Forest Regressor
* Support Vector Regressor
* XGBoost Regressor *(if installed)*

**Model performance compared using:**

* Mean Squared Error (MSE)
* R² Score
* Cross-Validation R²
* Training Time

### 4. Feature Importance

* Feature impact measured using Random Forest

### 5. Performance Classification

Students are categorized into:

* **Excellent**: 90 and above
* **Good**: 70–89
* **Needs Support**: Below 70

Random Forest Classifier is used to identify which students fall into each category.

---

## 📈 Results

* Random Forest performed best overall in both regression and classification tasks.
* Top influential features: `previous_exam_score`, `class_participation_score`, and `learning_hours_per_week`.

---

## ✅ Conclusion

This project demonstrates how data-driven insights can help coaching institutes like **EduQuest** take proactive steps to support students. By identifying weak areas early, educators can tailor their teaching strategies and improve student outcomes.

---

## 🙏 Acknowledgment

This project was developed as part of an internship at **YBI Foundation**. Their guidance and real-world use case helped shape this learning experience.

---

## 💻 Author

Asmi Dagar

> Feel free to fork, use, or build upon this project for educational purposes!
