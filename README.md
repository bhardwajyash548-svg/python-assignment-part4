# python-assignment-part4

# 🎓 Student Performance Analysis & Prediction

## 📌 Project Overview
This project focuses on analysing student performance data using **Pandas, Matplotlib, Seaborn, and Machine Learning (scikit-learn)**.

The goal is to:
- Explore and understand student data
- Visualize patterns and trends
- Build a machine learning model to predict whether a student will **Pass or Fail**

---

## 📂 Dataset
The dataset contains information about 15 students with the following features:

- Math, Science, English, History, PE scores
- Attendance percentage
- Study hours per day
- Final result (Pass = 1, Fail = 0)

---

## ⚙️ Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧠 Task 1 — Data Exploration

Performed basic data analysis using Pandas:

- Loaded dataset using `pd.read_csv()`
- Displayed first 5 rows
- Checked dataset shape and data types
- Generated summary statistics
- Counted pass vs fail students
- Calculated average scores for pass and fail groups
- Identified student with highest overall average

---

## 📊 Task 2 — Data Visualization (Matplotlib)

Created 5 visualizations:

1. **Bar Chart** — Average score per subject  
2. **Histogram** — Distribution of math scores with mean line  
3. **Scatter Plot** — Study hours vs average score (Pass vs Fail)  
4. **Box Plot** — Attendance comparison (Pass vs Fail)  
5. **Line Plot** — Math vs Science scores for all students  

All plots were saved as `.png` files.

---

## 📈 Task 3 — Data Visualization (Seaborn)

Used Seaborn for better statistical visualization:

- Bar plots comparing Math and Science scores (Pass vs Fail)
- Scatter plot of Attendance vs Average Score with regression lines

### 🔍 Observation:
Seaborn made it easier to create visually appealing plots with less code, while Matplotlib provided more control for customization.

---

## 🤖 Task 4 — Machine Learning Model

Built a classification model to predict Pass/Fail.

### Steps:
- Selected features and target
- Split data into training (80%) and testing (20%)
- Scaled features using `StandardScaler`
- Trained a **Logistic Regression model**

### 📊 Results:
- Training Accuracy: (varies)
- Test Accuracy: (varies due to small dataset)

### 🔍 Key Insight:
- Features like **study hours** and **attendance** have strong impact on performance.

---

## 📌 Feature Importance
- Extracted model coefficients
- Plotted feature importance using a horizontal bar chart
- Positive values → increase chance of passing  
- Negative values → increase chance of failing  

---

## 🧪 New Student Prediction
Tested model on a new student input and predicted:
- Pass/Fail result
- Probability score

---


## 💡 Conclusion

This project helped in understanding:
- Data analysis using Pandas
- Data visualization using Matplotlib & Seaborn
- Machine learning workflow using scikit-learn

Even with a small dataset, we can build a complete pipeline from data exploration to prediction.

---

## 🙌 Author
**Yash Bhardwaj**
