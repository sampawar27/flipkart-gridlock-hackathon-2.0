# flipkart-gridlock-hackathon-2.0
End-to-End ML pipeline for Traffic Demand Prediction built during Flipkart Gridlock Hackathon 2.0.

# 🚦 Traffic Demand Prediction | Flipkart Gridlock Hackathon 2.0

> From "Where is the workspace?" to building a complete ML pipeline.

## 📌 Overview

This repository contains my solution for the **Traffic Demand Prediction** challenge from **Flipkart Gridlock Hackathon 2.0**.

The objective was to predict traffic demand using geographical, temporal, weather, and road-related features.

### 🏆 Best Public Score

**86.03566** ✅

---

## 📊 Dataset

| Dataset | Shape |
|----------|-------|
| Train | 77,299 × 11 |
| Test | 41,778 × 10 |

---

## 🔍 Exploratory Data Analysis

Some observations:

- RoadType was the most important feature.
- Demand peaked around midday.
- Temperature showed almost no correlation with demand.
- Highways had significantly higher traffic demand.
- Geohash contributed heavily to predictions.

---

## ⚙️ Feature Engineering

- Extracted hour and minute from timestamp
- Created `midday_peak`
- Created `evening_low`
- Encoded categorical variables
- Handled missing values

---

## 🤖 Models Used

### Random Forest Regressor

RMSE: **0.03427**

### CatBoost Regressor

RMSE: **0.03430**

---

## 📈 Results

Public Leaderboard Score:

**86.03566**

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- CatBoost

---

## 🚀 Key Learning

Hackathons are not only about winning. They are about learning, experimenting, and becoming better than yesterday.

```
❌ Didn't qualify for Round 2
✅ Built my first complete ML pipeline
```

---

## 📬 Connect With Me

LinkedIn: www.linkedin.com/in/samruddhipawar27
