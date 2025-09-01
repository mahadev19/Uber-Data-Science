# 🚖 Uber Data Science Analysis

This project explores Uber ride booking data to gain insights into ride patterns, user behavior, and trends using Python data science libraries. It also applies **Machine Learning techniques** for predictive modeling. The dataset is sourced from Kaggle and analyzed step by step in a Jupyter Notebook.

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
- **Scikit-learn** – Machine Learning models
- **KaggleHub** – To download dataset

---

## 📊 Analysis Performed

### 1. Data Preprocessing
- Loaded CSV data  
- Handled missing values  
- Converted datetime columns into features (day, month, weekday, hour)  
- Encoded categorical variables  

### 2. Exploratory Data Analysis (EDA)
- Ride distribution by **hours, weekdays, and months**  
- Pickup vs Drop location trends  
- Ride status distribution (Completed, Cancelled, Incomplete)  
- Payment method preferences  
- Correlation heatmaps and count plots  

### 3. Machine Learning Models
- **Feature Engineering**: Extracted time-based and categorical features  
- **Classification Models** (predicting ride status):  
  - Logistic Regression  
  - Random Forest  
  - Decision Tree  
- **Clustering**: KMeans for grouping rides by locations and patterns  
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score  

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/mahadev19/Uber-Data-Science.git
