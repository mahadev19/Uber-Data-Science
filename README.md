# 🚖 Uber Data Science Analysis

This project explores Uber ride booking data to gain insights into ride patterns, user behavior, and trends using Python data science libraries. The dataset is sourced from Kaggle and analyzed step by step in a Jupyter Notebook.

---

## 📂 Dataset
- **Source:** [Uber Ride Analytics Dashboard - Kaggle](https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard)
- **File Used:** `ncr_ride_bookings.csv`
- Contains booking details such as ride status, pickup/drop information, payment type, and timestamps.

---

## 🛠️ Technologies & Libraries
- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computations
- **Matplotlib & Seaborn** – Data visualization
- **KaggleHub** – To download dataset

---

## 📊 Analysis Performed
1. **Data Loading & Cleaning**
   - Read CSV data
   - Handled missing values
   - Converted datetime columns into features like day, month, weekday, and hour

2. **Exploratory Data Analysis (EDA)**
   - Summary statistics of rides
   - Ride distribution across time (hours, weekdays, months)
   - Analysis of pickup vs drop locations
   - Ride status (Completed, Cancelled, Incomplete)
   - Payment method trends

3. **Visualization**
   - Count plots for categorical features
   - Heatmaps for correlation
   - Line/bar charts for time-based analysis

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/mahadev19/Uber-Data-Science.git
