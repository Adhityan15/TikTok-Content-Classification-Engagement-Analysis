# 📊 Executive Summary – TikTok Project

## 🎯 Objective

TikTok leadership approved a project to build a model that classifies user-generated videos as either **claims** or **opinions**. This report summarizes early insights from dataset inspection and engagement trend analysis to inform model development.

---

## 🧾 Dataset Observations

- **Data Types:** Mixed (numeric + categorical)
- **Missing Values:** Present in a few engagement columns (to be cleaned)
- **Notable Fields:**
  - `claim_status` (target variable)
  - `author_ban_status` (behavioral indicator)
  - Engagement: views, likes, shares, comments

---

## 📊 Key Insights

1. **Distribution:**
   - The dataset contains both *claims* and *opinions* in significant quantities.
   - `claim_status` is fairly balanced.

2. **Engagement by Claim Type:**
   - Opinion-based videos show **slightly better engagement per view**.
   - Claims tend to have **higher raw view counts**.

3. **Author Ban Impact:**
   - Banned authors have **lower engagement metrics** across the board.
   - May indicate behavior violation patterns or reduced visibility.

4. **Engineered Features:**
   - `likes_per_view`, `shares_per_view`, and `comments_per_view` were added.
   - These help measure relative audience interest beyond absolute numbers.

---

## 📌 Recommendations

- Clean null and outlier values
- Normalize categorical variables for modeling
- Prioritize `claim_status`, `author_ban_status`, and `likes_per_view` for prediction
- Visualize relationships using boxplots and heatmaps

---

## 📅 Prepared For

**Rosie Mae Bradshaw**  
TikTok Data Strategy Lead  
June 2025

---

Prepared by: **Adhityan R**  
Role: Junior Data Analyst  
