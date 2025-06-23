# 📊 Student Academic Performance - Exploratory Data Analysis (EDA)

This project analyzes a simulated dataset of student academic performance to uncover patterns, identify potential predictors of success, and guide future interventions in education.
[Watch Video Walkthrough](https://www.loom.com/share/50f776c238ee42d4afbbfe9cd702b49b?sid=9f5f8152-267d-485a-9cbd-378fbdda91b6)


---

## 📁 Dataset

**Source**: [Kaggle - Student Academic Performance Simulation (4000 samples)](https://www.kaggle.com/datasets/firedmosquito831/student-academic-performance-simulation-4000)

**Features include**:
- `Gender`
- `HoursStudied/Week`
- `Tutoring`
- `Region`
- `Attendance(%)`
- `Parent_Education`
- `Exam_Score` (Target)

---

## 🧠 Objectives

- Perform a clean and complete EDA on student data.
- Visualize patterns, distributions, and correlations.
- Handle missing values using appropriate strategies.
- Respectfully analyze low- and high-performing students.
- Lay the foundation for future predictive modeling.

---

## 📌 Key Insights

- **Exam Scores** are positively correlated with:
  - `HoursStudied/Week`
  - `Attendance(%)`
  - `Parent_Education` level
- Categorical features like `Gender` and `Region` showed **less correlation** but were still analyzed.
- Missing values were primarily found in `Parent_Education` and `Attendance(%)`, and handled using mode and mean imputation respectively.
- Outliers in exam scores were retained as they reflect **meaningful real-world variation** (e.g., high achievers and struggling learners).

---

## 🔍 EDA Steps Performed

- Data overview: `.shape`, `.info()`, `.describe()`, `.head()`
- Missing data heatmap and handling
- Feature distribution histograms
- Correlation heatmap
- Count plots for categorical variables
- Strategy discussion on outliers and feature relevance

---

## 📈 Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## ✨ Future Improvements

- Build a predictive model (e.g., linear regression or random forest) to estimate `Exam_Score`.
- Use SHAP or feature importance to explain model decisions.
- Explore non-linear relationships (e.g., decision trees, clustering).
- Turn insights into a dashboard using Streamlit or Dash.

---

## 🤝 Respect & Ethics

All analysis is done with respect for all learners:
- I avoid labeling students as "dumb" or "smart".
- Instead, we focus on **learning patterns**, **support needs**, and **achievement levels**.
- Terms like *struggling learners* and *high achievers* are used to reflect diverse academic journeys respectfully.

---

## 📜 License

This project is for educational and non-commercial use only. Please credit the original dataset creator on Kaggle if reused.

