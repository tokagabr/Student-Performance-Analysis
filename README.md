# 🎓 Student Performance Analysis
> Python · Pandas · NumPy

A data analysis project exploring academic performance patterns across departments using a real-world messy dataset.

---

## 📌 Objective
Identify key factors affecting student performance and surface actionable insights from raw, uncleaned academic data.

---

## 🛠️ Tools Used
- Python, Pandas, NumPy

---

## 🔍 What's Inside

| Part | Description |
|------|-------------|
| Part 1 | Basic Exploration — shape, stats, missing values, duplicates |
| Part 2 | Data Cleaning — fix types, handle nulls, remove duplicates |
| Part 3 | Feature Engineering — PassStatus, AttendanceCategory, AgeGroup |
| Part 4 | Data Analysis — department averages, graduation rates, top students |
| Part 6 | Insights & Conclusions |

---

## 💡 Key Findings

- **Attendance strongly predicts performance** — Pearson correlation: **0.78**
- **Arts department** leads in score (88 avg), graduation rate (85.7%), and attendance (90.9%)
- **Science department** showed a 0% graduation rate despite passing scores — flagged as anomaly
- Dataset contained **21 duplicate records** — surfaced a data entry process issue

---

## ▶️ How to Run

```bash
pip install pandas openpyxl numpy
python students_analysis.py
```

---

## 📁 Files
```
├── students_analysis.py   # Full analysis script
└── students.xlsx          # Dataset
```
