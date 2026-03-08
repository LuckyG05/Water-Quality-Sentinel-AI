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

## Project Visuals

### 1. AI Model Insights
*The Random Forest model identified Sulfate and pH as the most critical factors for water potability.*

**The Correlation Heatmap:** Initial exploratory data analysis showed weak linear correlations, necessitating a machine learning approach to identify hidden safety patterns.

<img width="562" height="504" alt="Screenshot 2026-03-08 222029" src="https://github.com/user-attachments/assets/8b741fbc-3aaa-4112-b406-72ee43d14992" />

**Random Forest Feature Importance:**  Mathematically identifying Sulfate and pH as the primary indicators for global water safety

<img width="556" height="483" alt="Screenshot 2026-03-08 222125" src="https://github.com/user-attachments/assets/daceb604-31e8-40a7-87f2-64faabd93a25" />

### 2. Interactive Risk Dashboard
*A comprehensive view of global water safety using Power BI. Green represents safe zones, while Red highlights at-risk areas.*
<img width="1190" height="669" alt="image" src="https://github.com/user-attachments/assets/47263214-c7a7-455b-8162-a6356a63306f" />

<img width="1194" height="673" alt="image" src="https://github.com/user-attachments/assets/5ba78aff-b4d3-461b-b752-0078b0969c43" />

### 3. Dynamic Analysis & Tooltips
*Users can interact with the Sulfate slider to see real-time changes in safety metrics across different regions.*

<img width="1188" height="671" alt="Screenshot 2026-03-08 223752" src="https://github.com/user-attachments/assets/90017c13-f8cb-47a8-b7a2-14034cce7e14" />

