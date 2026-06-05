# Behavioral Analytics for Social Media Addiction & Brain Rot Detection

## Overview
A behavioral analytics and machine learning project that analyzes social media usage patterns, engineers digital well-being indicators, develops a custom Brain Rot Index (BRI), and identifies user personas through clustering techniques. The system helps uncover addictive usage behaviors such as excessive scrolling, compulsive checking, and attention fragmentation.

The project combines behavioral feature engineering, clustering, visualization, and machine learning to identify risky digital habits such as excessive scrolling, compulsive checking, attention fragmentation, and late-night social media usage.

## 🚀 Key Features
- Custom Brain Rot Index (BRI) (0–100)
- Behavioral Feature Engineering
- User Persona Discovery using K-Means Clustering
- PCA-Based Persona Visualization
- XGBoost Regression Model
- Feature Importance Analysis

## Dataset Description

### Base Dataset
https://www.kaggle.com/datasets/zahranusratt/student-social-media-addiction-analysis-dataset

### Final Dataset
- 705 records
- 30 features
- Original features + engineered behavioral features

## 📊 Engineered Behavioral Features
- App Switch Frequency
- Notification Response Time
- Relapse Frequency
- Short Form Content Ratio
- Attention Recovery Time
- Late Night Usage Index
- Usage Escalation Rate
- Session Binge Score

  
## 👥 User Personas Identified
Persona	Description
- 🟢 Healthy Users	Low addiction, controlled usage habits
- 🟡 Casual Users	Moderate engagement and balanced behavior
- 🟠 Frequent Scrollers	High app-switching and scrolling activity
- 🔴 Doom Scrollers	High addiction, binge scrolling, compulsive checking

## Machine Learning Model
Model Used : XGBoost Regressor
The Brain Rot Index (BRI) prediction task was formulated as a regression problem, where the objective was to estimate a user's BRI score based on behavioral and psychological indicators.

## 📂 Project Structure
Social-Media-Addiction-Detection/
│
├── data/
│   ├── Students Social Media Addiction.csv
│   └── enriched_social_media_dataset.csv
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Behavioral_Feature_Engineering.ipynb
│   └── 03_XGBoost_Regressor.ipynb
│
├── images/
│   ├── correlation_heatmap.png
│   ├── brain_rot_distribution.png
│   ├── persona_pca.png
│   └── feature_importance.png
│
└── README.md


## 👩‍💻 Author

Medha Jha
