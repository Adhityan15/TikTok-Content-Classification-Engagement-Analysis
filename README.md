📊 TikTok Content Classification & Engagement Analysis
A complete Python-based data science project analyzing user-generated TikTok video data. Developed as part of the Google Advanced Data Analytics Professional Certificate , this project simulates a real-world role at TikTok, where we prepare video engagement data for classification modeling and strategic insights.

🎯 Project Objectives
Inspect and clean raw TikTok video data

Explore engagement patterns across claim types and author status

Engineer features to support classification modeling

Build predictive models to classify videos as claims or opinions

Communicate insights through visualizations and stakeholder-ready summaries

📁 Dataset Overview
Attribute	Description
File Name	tiktok_dataset.csv
Source	Simulated TikTok data for educational purposes
Rows	~[Fill after inspection]
Columns	Includes video metrics and categorical indicators
Key Columns:
claim_status: Claim or Opinion

author_ban_status: Banned or Active

video_view_count, video_like_count, video_share_count, video_comment_count: Engagement metrics

🛠️ Tools & Technologies
Python 3.x

pandas – Data manipulation

NumPy – Numerical operations

matplotlib & seaborn – Visualization

scikit-learn – Classification modeling

Jupyter Notebook – Interactive development

🔍 Workflow Summary
1. 📥 Data Import & Initial Exploration
Loaded dataset and inspected structure

Validated column types and identified missing values

Flagged outliers in engagement metrics

2. 🧹 Data Cleaning
Removed or imputed missing values

Normalized engagement metrics

Converted categorical variables for modeling

3. 📊 Exploratory Data Analysis (EDA)
Distribution plots for claims vs opinions

Engagement comparisons by claim_status and author_ban_status

Correlation analysis between metrics

4. 🧪 Feature Engineering
Created interaction ratios:

likes_per_view, shares_per_view, comments_per_view

Encoded categorical variables

Scaled numerical features for modeling

5. 📈 Predictive Modeling
Built classification models to predict claim_status:

Logistic Regression

Decision Tree

Random Forest

Evaluated models using:

Accuracy, Precision, Recall, F1 Score

Confusion Matrix and ROC Curve

6. 📊 Visualization & Communication
Created bar charts, boxplots, and heatmaps

Summarized insights in stakeholder-friendly markdown reports

Proposed dashboard structure for executive presentation

💡 Key Insights
Claims receive slightly higher average views, but opinions drive better engagement per view

Banned authors show significantly lower interaction rates

Feature ratios like likes_per_view are strong predictors of content type

Random Forest achieved highest classification accuracy (~[insert value])

🚀 Next Steps
Tune hyperparameters for model optimization

Explore NLP features from video captions or hashtags

Deploy model via Flask or Streamlit for internal testing

Build interactive dashboard for TikTok content strategists

✨ Author
Adhityan R
