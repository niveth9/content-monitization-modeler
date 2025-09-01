# 📊 Content Monetization Modeler

## 📌 Project Overview
YouTube has become a primary source of income for creators and media companies. However, ad revenue depends on several factors such as video engagement, audience demographics, and watch time. This project builds a machine learning model that predicts YouTube ad revenue (`ad_revenue_usd`) using video performance metrics. A Streamlit web application is also developed to allow interactive predictions and visualization.

## 🎯 Objectives
- Predict YouTube ad revenue using regression models
- Perform Exploratory Data Analysis (EDA) to understand key drivers of revenue
- Apply data preprocessing, feature engineering, and categorical encoding
- Compare multiple regression models and select the best one
- Build a Streamlit app for user interaction and revenue forecasting

## 🛠️ Skills & Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn, XGBoost, Streamlit, Joblib/Pickle

## 📂 Dataset Details
- **Name:** YouTube Monetization Modeler  
- **Format:** CSV (~122,000 rows)  
- **Target Variable:** `ad_revenue_usd`

### Key Columns
- `video_id` – Unique identifier  
- `date` – Upload/report date  
- `views`, `likes`, `comments` – Performance metrics  
- `watch_time_minutes`, `video_length_minutes` – Engagement & content length  
- `subscribers` – Channel subscriber count  
- `category`, `device`, `country` – Contextual info  
- `ad_revenue_usd` – Revenue generated (target)

## 🔑 Approach
1. Data Understanding – Load and inspect dataset  
2. EDA – Explore trends, correlations, and outliers  
3. Preprocessing – Handle missing values (~5%), remove duplicates (~2%), encode categorical variables, scale/normalize numerical features if needed  
4. Feature Engineering – Create new features like `engagement_rate = (likes + comments) / views`  
5. Model Building – Train multiple regressors: Linear Regression, Ridge/Lasso, Random Forest, Gradient Boosting, XGBoost  
6. Evaluation Metrics – Compare models using R², RMSE, MAE  
7. Deployment – Streamlit app for predictions & insights  

## 🚀 Results
- Developed a trained regression model for ad revenue prediction  
- Identified top features influencing revenue  
- Built a Streamlit application for interactive testing  

## 📈 Streamlit App Features
- Input video performance data → Predict expected Ad Revenue  
- Interactive plots for views vs revenue, engagement rate, and category insights  
- User-friendly interface for YouTubers & media companies  

## 📂 Project Structure
