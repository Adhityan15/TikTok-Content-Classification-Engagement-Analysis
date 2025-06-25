# 📊 TikTok Content Classification & Engagement Analysis

Welcome to the **TikTok Project**, developed as part of the Google Data Analytics Professional Certificate – Course 2: *Get Started with Python*.

This project simulates a real-world role as a data professional working for TikTok. The objective is to inspect, clean, and summarize user-generated video data to uncover trends and prepare for a claims classification model.

---

## 🧾 Project Overview

TikTok leadership has approved a proposal to build a machine learning model that classifies videos into **claims** or **opinions**. To begin, exploratory data analysis (EDA) is needed to understand data quality and uncover key engagement patterns.

This notebook includes:

- Initial inspection of the TikTok dataset
- Data type validation and missing value checks
- Engagement trend analysis
- Feature engineering to support future modeling

---

## 📁 Dataset Summary

**File:** `tiktok_dataset.csv`  
**Rows:** ~??? (fill after inspection)  
**Columns:** Includes video metrics and categorical indicators such as:

- `claim_status`: Indicates if a video is a *claim* or *opinion*
- `author_ban_status`: Indicates if a content author is banned
- `video_view_count`, `video_like_count`, `video_share_count`, `video_comment_count`: Engagement metrics

---

## 🛠️ Technologies Used

- Python 3.x
- pandas
- NumPy
- Jupyter Notebook

---

## 🔍 Analysis Performed

1. **Data Loading & Summary**
   - Used `head()`, `info()`, `describe()` for basic inspection
   - Identified nulls, data types, and outliers

2. **Exploration by `claim_status`**
   - Distribution of claims vs opinions
   - Mean & median view counts by claim type

3. **Author Ban Status Impact**
   - Grouped by `author_ban_status` and analyzed likes, views, and shares
   - Compared engagement rates of banned vs active users

4. **Feature Engineering**
   - Created `likes_per_view`, `shares_per_view`, and `comments_per_view`
   - Grouped by `claim_status` and `author_ban_status` to compare interaction rates

---

## 💡 Key Findings

- **Claim vs Opinion:** The dataset has a balanced mix of both, but claims tend to receive **slightly higher average view counts**.
- **Banned Authors:** Users with a ban status tend to have **lower overall engagement**.
- **Engagement Metrics:** Likes, comments, and shares **per view** are generally higher for **opinion-based** videos.
- **Correlations:** Claim status is somewhat correlated with lower engagement ratios per view.

---

## 🚀 Next Steps

1. Handle missing values and normalize data
2. Perform visual EDA using `Seaborn` or `Matplotlib`
3. Begin predictive modeling using logistic regression or tree-based classifiers
4. Develop a dashboard to communicate findings to stakeholders

---

## 📎 Files Included

- `TikTok_Project.ipynb`: Jupyter notebook with code
- `Executive_Summary.md`: Stakeholder-friendly summary
- `README.md`: GitHub project documentation
- `tiktok_dataset.csv`: (If allowed for sharing or add link if hosted externally)

---

## ✨ Author

**Adhityan R**  
Google Data Analytics Learner | Aspiring Data Scientist  
GitHub: [Adhityan15](https://github.com/Adhityan15)
