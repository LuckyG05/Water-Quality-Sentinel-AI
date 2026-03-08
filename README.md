# Global Water Quality Sentinel: AI Risk Assessment

## Project Overview
This project is an end-to-end Data Science and Business Intelligence solution developed during my **Microsoft Elevate Internship**. The goal is to predict water potability using Machine Learning and provide real-time risk analysis through an interactive Power BI dashboard.

## Key Features
- **Predictive Modeling:** Built a Random Forest Classifier to predict if water is safe for consumption (Potability).
- **Interactive Dashboard:** Designed a Power BI sentinel to monitor 3,275+ water samples globally.
- **Risk Identification:** Integrated AI-driven insights to highlight **Sulfate**, **pH**, and **Hardness** as primary risk factors.
- **Dynamic Filtering:** Real-time slicers to analyze chemical concentrations and geographic safety zones.

## Tech Stack
- **Languages:** Python (Jupyter Notebook)
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **BI Tool:** Power BI Desktop
- **Model:** Random Forest (Ensemble Learning)

## Data Insights
- **Model Accuracy:** 68.29%
- **Top Driver:** Sulfate levels were identified as the most significant predictor of water safety.
- **Geographic Mapping:** Visualized "Safe" (Green) and "Unsafe" (Red) zones based on AI predictions.

## Repository Structure
- `Water_Quality_Analysis.ipynb`: Python code for EDA, Data Cleaning, and ML Modeling.
- `Final_Water_Quality_Data.csv`: Pre-processed dataset for visualization.
- `Water_Quality_Dashboard.pbix`: Interactive Power BI dashboard file.

## 🖼️ Project Visuals

### 1. AI Model Insights
*The Random Forest model identified Sulfate and pH as the most critical factors for water potability.*
![Feature Importance](path/to/your/feature_importance_image.png)

**Random Forest Feature Importance:**  Mathematically identifying Sulfate and pH as the primary indicators for global water safety
<img width="556" height="483" alt="image" src="https://github.com/user-attachments/assets/108df9a0-9d1f-40d2-8325-1a20743d841a" />


### 2. Interactive Risk Dashboard
*A comprehensive view of global water safety using Power BI. Green represents safe zones, while Red highlights at-risk areas.*
![Power BI Dashboard](path/to/your/dashboard_image.png)

### 3. Dynamic Analysis & Tooltips
*Users can interact with the Sulfate slider to see real-time changes in safety metrics across different regions.*
![Dashboard Interactivity](path/to/your/tooltip_image.png)
