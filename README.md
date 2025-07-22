# 📊 HR Data Analysis

A data analytics project to explore HR trends and employee behaviors using Python and visualization tools. This project performs **Exploratory Data Analysis (EDA)** on a real-world HR dataset to uncover key insights about **employee satisfaction**, **attrition**, and **performance**.

---
```bash
HR-Data-Analysis/
│
├── data/
│   └── HR Data.csv              # Raw dataset (HR data)
│
├── notebooks/
│   └── Hr_analysis.ipynb        # Jupyter Notebook with EDA and visualizations
│
├── outputs/                     # (Optional) Graphs, plots, or summary CSVs
│   └── attrition_insights.png   # Sample output image
│
├── README.md                    # Project documentation (this file)
├── requirements.txt             # (Optional) Python dependencies
└── LICENSE                    # (Optional) License file

```
---

## 🎯 Objective

This project aims to:

- Understand the factors contributing to employee turnover.
- Analyze job satisfaction, promotion history, and workload.
- Provide visual summaries of key HR metrics.
- Suggest areas for improvement in HR practices.

---

## 📊 Dataset Overview

The dataset `HR Data.csv` contains the following features:

| Column Name             | Description                              |
|-------------------------|------------------------------------------|
| `satisfaction_level`    | Employee satisfaction score               |
| `last_evaluation`       | Last performance evaluation score         |
| `number_project`        | Number of projects assigned               |
| `average_montly_hours`  | Average monthly working hours             |
| `time_spend_company`    | Years spent at the company                |
| `Work_accident`         | Whether employee had a work accident      |
| `left`                  | Employee attrition (1 = left, 0 = stayed) |
| `promotion_last_5years` | Promotion status in last 5 years          |
| `sales`                 | Department                                |
| `salary`                | Salary level (`low`, `medium`, `high`)   |

---

## 🧰 Tech Stack

- 🐍 Python
- 📗 Pandas
- 📘 Seaborn
- 📊 Matplotlib
- 📒 Jupyter Notebook

---

## 📈 Key Insights

- Employees with low satisfaction levels are more likely to leave.
- High workload and long tenure can contribute to attrition.
- Promotion and salary level play significant roles in retention.
- Departmental trends can help identify specific issues.

*(Detailed insights are available in the Jupyter Notebook.)*

---

## ▶️ Getting Started

To run this project on your local machine:

```bash
git clone https://github.com/yourusername/hr-data-analysis.git
cd hr-data-analysis
jupyter notebook Hr_analysis.ipynb

Make sure Python and Jupyter Notebook are installed in your environment.

Future Enhancements:

✅ Build a predictive model for employee attrition using ML.

📊 Create a live HR dashboard with Streamlit or Dash.

🤖 Apply clustering to discover employee segments.

```

🧑‍💻 Author

Arunachalam

AI & Data Science Enthusiast

📧 phoenixdark318@gmail.com

🔗 https://www.linkedin.com/in/arunachalam-g-93b483218/





