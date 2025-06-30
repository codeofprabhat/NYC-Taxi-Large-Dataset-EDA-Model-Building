# NYC-Taxi-Large-Dataset-EDA-Model-Building

# NYC Taxi Trip Analysis: EDA, Regression & FiveThirtyEight Visualizations

This project provides a comprehensive exploratory data analysis (EDA), feature engineering, and regression modeling pipeline on the **New York City Taxi Trip Duration** dataset. It also incorporates **FiveThirtyEight-style visualizations** to communicate insights effectively.

Inspired by a Kaggle Notebook:  
[Stephanie Stallworth's NYC Taxi EDA + Regression + Fivethirtyeight Viz](https://www.kaggle.com/code/stephaniestallworth/nyc-taxi-eda-regression-fivethirtyeight-viz)

---

## 🚖 Project Overview

The objective is to analyze patterns in NYC taxi trip data, understand what affects trip duration, and build predictive models using regression techniques. The workflow follows:

- Data preprocessing & cleaning
- Feature engineering (temporal, geospatial)
- Exploratory data visualization (EDA)
- Regression modeling (Linear, Ridge, Lasso)
- Evaluation metrics
- Visual storytelling using FiveThirtyEight-inspired plots

---

## 📁 Dataset

The dataset used is from Kaggle's **NYC Taxi Trip Duration** competition:

- Train: `train.csv` (145k+ records)
- Test: `test.csv`
- Features include pickup/dropoff times and locations, passenger count, etc.

📌 **Link**: https://www.kaggle.com/competitions/nyc-taxi-trip-duration/data

---

## 🧰 Technologies Used

- **Python 3.8+**
- **Pandas, NumPy** – data manipulation
- **Matplotlib, Seaborn, Plotly** – visualization
- **Scikit-learn** – regression modeling
- **Geopy** – distance calculation (Haversine)
- **Datetime & calendar** – time feature engineering
- **Matplotlib styles** – FiveThirtyEight theme

---

## 📊 Key Features & Techniques

### ✅ EDA
- Temporal analysis (hour, day, weekday)
- Trip distance & duration distribution
- Outlier detection
- Geospatial mapping of pickups and drop-offs

### ✅ Feature Engineering
- Time-based features
