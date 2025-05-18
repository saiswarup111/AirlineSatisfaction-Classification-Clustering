

# ✈️ Airline Passenger Satisfaction - Classification & Clustering

This project analyzes passenger satisfaction using the Kaggle Airline Passenger Satisfaction dataset (~26,000 records). It applies supervised learning for satisfaction prediction and unsupervised learning to segment passengers into meaningful clusters.

## 🔍 Objective
- **Classification**: Predict if a customer is *satisfied* or *dissatisfied* based on flight and service features.
- **Clustering**: Segment customers into distinct groups for targeted business insights.

## 📊 Dataset Overview
- Source: Kaggle  
- Features: 23 (mixed numeric & categorical)  
- Target: `Satisfaction` (Satisfied / Dissatisfied)

## 🧹 Preprocessing
- Handled 83 missing values by dropping rows (<0.1% of data)
- Dummy encoded categorical variables
- Label encoded the target
- Scaled features for model training

## 🧠 Supervised Learning (Classification)
- Algorithms used: Decision Tree, Random Forest, AdaBoost, KNN, Naive Bayes, LDA, QDA
- Best Model: **Decision Tree**
  - Accuracy: **91.67%**
  - AUC: **0.98**

## 📈 Unsupervised Learning (Clustering)
- Applied **K-Means Clustering**
- Optimal clusters: **4** (using Elbow Method & Silhouette Score)
- Cluster insights reveal differences in customer type, travel distance, and satisfaction levels

## 💼 Business Insights
- Personal travel, younger age, and better check-in service correlate with higher satisfaction
- Long-distance travelers and delayed flights are more likely to report dissatisfaction
- Disloyal flyers showed surprising satisfaction — a key loyalty opportunity

## 📁 Files
- `Airline_Satisfaction_Analysis.ipynb`: Complete Jupyter notebook with analysis and modeling
- `airline_passenger_satisfaction.csv`: Dataset (not included, downloadable from Kaggle)


