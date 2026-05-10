# Causal Modeling and Prediction of Instagram Engagement and Follower Growth

## Overview
This project presents a unified analytical framework that combines causal inference and predictive modeling to analyze Instagram engagement patterns and forecast follower growth.

Unlike traditional analytics systems that rely only on correlation-based insights, this framework identifies both:
- What influences engagement (predictive modeling)
- Why it influences engagement (causal inference)

The system integrates machine learning, causal analysis, time-series forecasting, and explainable AI to provide interpretable and data-driven social media insights.

---

## Problem Statement
Most existing Instagram analytics systems:
- Depend primarily on correlation analysis
- Lack interpretability in predictions
- Fail to identify true causal drivers of engagement
- Provide limited strategic insights for content optimization

This project addresses these limitations through an integrated framework combining causal inference, predictive analytics, and explainable AI.

---

## Dataset
- Source: Instagram data collected using Instaloader
- Target Account: @natgeo
- Sample Size: 100 Instagram posts

### Features Collected
- Captions
- Hashtags
- Posting time
- Media type (image/video)
- Likes and comments
- Follower count trends

### Engineered Features
- Engagement Rate (ER)
- Follower Growth
- Sentiment polarity
- Caption length
- Hashtag count
- Emoji count

---

## Methodology

### Data Processing
- Text preprocessing and normalization
- Sentiment analysis
- Feature engineering
- Temporal encoding
- Engagement normalization

### Causal Inference Framework
- Directed Acyclic Graphs (DAGs)
- Propensity Score Matching (PSM)
- Average Treatment Effect (ATE)
- Inverse Probability Weighting (IPW)
- Doubly Robust Estimation

### Predictive Modeling
Implemented multiple predictive models including:
- Random Forest
- XGBoost
- ARIMA
- LSTM
- Prophet

### Explainable AI
- SHAP-based feature importance analysis
- Global and local interpretability
- Transparent model decision analysis

---

## System Architecture
Instagram Data → Feature Engineering → Causal Modeling → Predictive Modeling → SHAP Explainability → Engagement & Growth Forecasting

---

## Results
- Random Forest achieved the best predictive performance with:
  - R² Score: **0.8827**
  - MAE: **21097.16**
- Successfully identified key engagement drivers including:
  - Number of comments
  - Media type
  - Hashtag usage
  - Mentions
- Forecasted follower growth trends using Prophet and LSTM models
- Generated interpretable insights using SHAP explainability

---

## Performance Metrics
- R² Score: **88.27%**
- Mean Absolute Error (MAE): **21097.16**
- Comparative evaluation performed across multiple ML and forecasting models

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- TensorFlow / Keras
- ARIMA
- Prophet
- SHAP
- Instaloader
- Matplotlib
- Seaborn
- Streamlit

---

## Key Features
- Unified causal + predictive analytics framework
- Instagram engagement prediction
- Follower growth forecasting
- Explainable AI integration using SHAP
- Time-series forecasting
- Evidence-based social media strategy insights

---

## Applications
- Influencer marketing analytics
- Social media strategy optimization
- Content scheduling analysis
- Engagement forecasting
- Digital branding analytics

---

## Conclusion
This project demonstrates how causal inference and machine learning can be integrated to build an interpretable and predictive Instagram analytics framework. By distinguishing causation from correlation, the system provides more reliable and actionable insights for social media performance optimization.

---

## Future Work
- Extend the framework for multi-account comparative analysis
- Deploy as a real-time social media analytics dashboard
