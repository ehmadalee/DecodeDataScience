# 📊 DecodeDataScience

A beginner-friendly, notebook-based crash course in data science fundamentals — from raw Python arrays to a full predictive modeling project.

Each notebook builds on the last: **NumPy → Pandas → Matplotlib → Final Project**, with a glossary alongside to demystify the jargon as you go.

---

## 📁 What's inside

| File | Topic |
|---|---|
| [`00_Data_Science_Dictionary.md`](./00_Data_Science_Dictionary.md) | Glossary of core data science / Pandas / NumPy terms, explained with everyday analogies |
| [`01_Data_Science_Introduction.ipynb`](./01_Data_Science_Introduction.ipynb) | Setup, array dimensions & shape, vectorization & broadcasting, slicing, building your first DataFrame |
| [`02_NumPy.ipynb`](./02_NumPy.ipynb) | Core NumPy: arrays, operations, and numerical computing basics |
| [`03_Pandas.ipynb`](./03_Pandas.ipynb) | Core Pandas: DataFrames, Series, data wrangling |
| [`04_Matplotlib.ipynb`](./04_Matplotlib.ipynb) | Data visualization: plots, charts, and how to read them |
| [`05_Final_Project.ipynb`](./05_Final_Project.ipynb) | **Capstone:** Predicting Student Grades using everything from 01–04 |
| [`datasets/Student_performance_data _.csv`](./datasets/Student_performance_data%20_.csv) | Real dataset used throughout, especially in the final project |

---

## 🎓 The dataset

`Student_performance_data _.csv` contains per-student records with fields like:

`StudentID, Age, Gender, Ethnicity, ParentalEducation, StudyTimeWeekly, Absences, Tutoring, ParentalSupport, Extracurricular, Sports, Music, Volunteering, GPA, GradeClass`

It's used as the running example across the notebooks and is the basis for the prediction task in the final project.

---

## 🚀 Getting started

1. **Clone the repo**
   ```bash
   git clone https://github.com/<your-username>/DecodeDataScience.git
   cd DecodeDataScience
   ```

2. **Install dependencies**
   ```bash
   pip install numpy pandas matplotlib jupyter
   ```

3. **Launch Jupyter**
   ```bash
   jupyter notebook
   ```

4. **Follow the notebooks in order**, starting with `01_Data_Science_Introduction.ipynb`. Keep `00_Data_Science_Dictionary.md` open as a reference for any term that's unfamiliar.

---

## 🧭 Suggested learning path

```
00 (glossary, as needed)
   ↓
01 → 02 → 03 → 04 → 05
Intro   NumPy   Pandas   Matplotlib   Final Project
```

---

## 🙋 Who this is for

Anyone starting out in data science who wants a hands-on, example-driven path rather than a pure theory dump — the glossary in particular is aimed at people who are new to the vocabulary, not just the code.

---

## 📄 License

MIT License — see [`LICENSE`](./LICENSE) for details.
