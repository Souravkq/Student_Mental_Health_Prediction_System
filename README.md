#  Student Mental Health Prediction System

A Machine Learning and Data Science project that predicts student mental health risk using survey-based student data and classification algorithms.

---

#  Overview

This project focuses on analyzing student mental health conditions using Machine Learning techniques. The model learns patterns from student-related data such as academic pressure, CGPA, lifestyle, and other attributes to predict possible mental health risks.

The project was built using Python and Scikit-learn in Google Colab / Jupyter Notebook.

---

#  Features

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization using Graphs
- Machine Learning Model Training
- Prediction System
- Accuracy Evaluation
- Correlation Analysis

---

#  Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Handling |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Graphs |
| Scikit-learn | Machine Learning |

---

#  Dataset

Dataset used:

```text
students_mental_health_survey.csv
```

The dataset contains student-related information such as:
- Academic Performance
- Study Patterns
- Mental Health Indicators
- Lifestyle Habits
- Stress Factors

---

#  Machine Learning Algorithm

This project uses:

```text
Random Forest Classifier
```

The Random Forest model is trained to classify and predict mental health risk based on selected input features.

---

#  Project Workflow

```text
Dataset Collection
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Data Visualization
        ↓
Feature Selection
        ↓
Model Training
        ↓
Prediction
        ↓
Accuracy Evaluation
```

---

#  Visualizations Included

The project includes:
- Count Plots
- Histograms
- Correlation Heatmaps
- Distribution Analysis
- Feature Comparison Graphs

---

#  Installation

## Clone Repository

```bash
git clone https://github.com/Souravkq/student-mental-health-prediction.git
```

---

## Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

#  Running the Project

Open the notebook using:
- Google Colab
- Jupyter Notebook
- Jupyter Lab

Run all cells step by step.

---

#  Example Prediction

```python
sample = pd.DataFrame([[5, 8]], columns=X.columns)

prediction = model.predict(sample)

print(prediction)
```

Example Output:

```python
[0]
```

---

#  Model Accuracy

The project evaluates model performance using:

- Accuracy Score
- Classification Report

Example:

```python
print("Accuracy:", accuracy)
```

---

#  Project Structure

```text
student-mental-health-project/
│
├── students_mental_health_survey.csv
├── student_mental_health.ipynb
└── README.md
```

---

#  Future Improvements

Possible future upgrades:
- Deep Learning Integration
- Streamlit Dashboard
- Real-time Prediction System
- AI-based Student Assistant
- Interactive Web Application

---

#  Objectives

- Understand student mental health patterns
- Apply Machine Learning techniques
- Learn Data Science workflow
- Build a real-world prediction system

---

#  Learning Outcomes

Through this project, the following concepts were implemented:
- Data Preprocessing
- Feature Engineering
- Data Visualization
- Model Training
- Classification Algorithms
- Prediction Systems

---

#  Why

Developed as a Data Science and Machine Learning educational project.

---
