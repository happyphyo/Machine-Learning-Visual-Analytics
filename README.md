# Machine-Learning-Visual-Analytics
Machine Learning and Visual Analytics for Reusable Rocket Launch Success
# SpaceX Falcon 9 First Stage Landing Prediction

## Project Overview
This capstone project aims to predict the success of SpaceX Falcon 9 first-stage landings. By leveraging data science techniques, we analyze launch data to determine the factors that influence a successful landing, helping competitors estimate launch costs more effectively.

## Repository Contents
1. **1_Data_Collection_API.ipynb**: Harvesting data from the SpaceX API.
2. **2_Data_Wrangling.ipynb**: Data cleaning and feature engineering (creating the landing 'Class').
3. **3_EDA_SQL.ipynb**: Using SQL to query and explore the dataset.
4. **4_EDA_Visualization.ipynb**: Exploratory Data Analysis using Pandas, Matplotlib, and Seaborn.
5. **5_Interactive_Map_Folium.ipynb**: Building interactive maps to visualize launch site proximity.
6. **6_Plotly_Dash_App.py**: A real-time dashboard for interactive data exploration.
7. **7_Machine_Learning_Prediction.ipynb**: Building and evaluating classification models.

## Key Insights
- The **Decision Tree** model achieved the highest accuracy on the test set (83.33%).
- Launch sites near the coast and major transport infrastructure show higher success frequencies.
- Payload mass significantly impacts the success rate across different orbit types.
