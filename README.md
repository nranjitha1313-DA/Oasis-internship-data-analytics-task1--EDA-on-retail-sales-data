# 🚀 OIBSIP — Oasis Infobyte Summer Internship Program

**Track:** 📈 Data Analytics · **Level:** 1 · **Tasks Completed:** 1, 2 & 3

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Internship](https://img.shields.io/badge/Oasis%20Infobyte-SIP-purple)

---

## 👋 About This Repository

This repository contains my project submissions for the **Oasis Infobyte Summer Internship Program (OIBSIP)**, under the **📈 Data Analytics** track.


Per the internship's completion rules for Data Analytics, interns must complete **at least 3 tasks from Level 1 or Level 2 combined**. I chose to complete **all 3 tasks from Level 1**, which involved end-to-end machine learning pipelines — from data cleaning and EDA to model training, evaluation, and business interpretation.

---

## 🗂️ Repository Structure

Following OIBSIP's required naming convention `OIBSIP/[TrackName]-[Level/Task]-[ProjectName]/`, this repo is organized as:

```
OIBSIP/
│
├── DataAnalytics-L1-task1-EDA on retail sales data.ipynb
├── DataAnalytics-L1-task2-Customer segmentation.ipynb
├── DataAnalytics-L2-task3-Cleaning data using titanic dataset.ipynb
└── README.md   ← you are here 📍
```

Each task folder contains its own source code, a dedicated `README.md`, and supporting screenshots/output files, as required by the program guidelines.

---

## 📋 Task Summaries

### 1️⃣ 🏠 EDA on retail sales data

**Folder:** [`DataAnalytics-L1-task1-EDA on retail sales data`](./DataAnalytics-L1-task1-EDA on retail sales data)

**🎯 Objective:** To examine raw store sales numbers and uncover hidden patterns—like which products sell best, when sales peak, and who the main buyers are—so the business can make smarter decisions.

**🛠️ Tech Stack:** Python, Pandas, NumPy (for data handling), Matplotlib & Seaborn (for charts and graphs), Jupyter Notebook.

**✅ What was done:**
- 🔍 Checked the dataset for errors, missing values, or duplicate records
- 🧩 Calculated basic business metrics like total revenue, average order value, and top-selling product categories.
- 📈Analyzed sales trends over time (e.g., monthly or seasonal spikes) and customer demographics (age and gender).
- 📉 Created bar charts, line graphs, and heatmaps to visually present the findings.

---

### 2️⃣ 🍷 Customer Segmentation using E-commerce Data

**Folder:** [`DataAnalytics-L1-task2-Customer Segmentation`](./DataAnalytics-L1-task2-Customersegmentation)

**🎯 Objective:** To group online shoppers with similar buying habits together (e.g., frequent big spenders vs. occasional discount hunters) so the company can send targeted marketing and personalized offers to each group.

**🛠️ Tech Stack:** Python, Pandas, Scikit-Learn (specifically the K-Means Clustering algorithm), Matplotlib & Seaborn, Jupyter Notebook.

**✅ What was done:**
- 🔍 Cleaned the transaction data and removed canceled orders or missing customer IDs.
- 📊 Created customer-level metrics—often using RFM analysis (Recency: how recently they bought, Frequency: how often they buy, Monetary: how much they spend).
- ⚖️ Scaled the numbers so large spending amounts didn't overpower other metrics.
- 🤖 Applied the K-Means machine learning algorithm to automatically group customers into distinct clusters and visualized these segments on scatter plots.

---

### 3️⃣ 💳 Cleaning data using titanic dataset

**Folder:** [`DataAnalytics-L2-task3-cleaning data`](./DataAnalytics-L2-task3-cleaningdata)

**🎯 Objective:** To take a messy, incomplete dataset of Titanic passengers and fix all its flaws so it is accurate, consistent, and ready for future analysis or machine learning models.

**🛠️ Tech Stack:** Python, Pandas, NumPy, Matplotlib/Seaborn (to spot outliers visually), Jupyter Notebook

**✅ What was done:**
- 📊 Handled Missing Data: Filled in missing passenger ages using the median age, filled missing boarding ports with the most common port, and dropped columns with too much missing data (like Cabin numbers).
- 🔍 Removed Duplicates & Irrelevant Info: Deleted duplicate rows and unnecessary columns (like Passenger ID or Ticket number) that don't help predict survival.
- 🤖 Fixed Outliers & Formats: Detected extreme values (like unusually high ticket fares) using box plots and converted text categories (like "Male" and "Female") into numbers (0 and 1) so algorithms can read them.

---

## 🧠 Key Learnings Across All 3 Tasks

**Data Cleaning**: Learned how to fix messy data (missing values and duplicates) before doing any analysis.

**Finding Patterns**: Learned how to look at raw numbers and spot useful trends, like best-selling products and busy shopping months.

**Customer Grouping**: Learned how to use basic machine learning (K-Means) to automatically group similar shoppers together.

**Visual Storytelling**: Learned how to turn boring tables of numbers into clear charts and graphs that anyone can understand.

**Python Tools**: Got hands-on practice using essential data tools like Pandas, Matplotlib, and Scikit-Learn.

---

## 🏅 About Oasis Infobyte SIP

The **Oasis Infobyte Summer Internship Program** is a hands-on internship where interns build real-world projects across various tech domains (Web Dev, Android, Java, Graphics Design, Data Science, Python, **Data Analytics**, and Cyber Security), submit them via GitHub, and demo them on LinkedIn.

- 🌐 Website: [oasisinfobyte.com](http://www.oasisinfobyte.com)
- 💼 LinkedIn: [Oasis Infobyte](https://in.linkedin.com/company/oasis-infobyte)

---

## 📬 Connect With Me

Feel free to explore each task folder for detailed notebooks, visualizations, and write-ups. Feedback and suggestions are always welcome! 🙌

<p align="center">Made with ❤️, Python 🐍, and a lot of pandas 🐼 during #oasisinfobyte</p>
