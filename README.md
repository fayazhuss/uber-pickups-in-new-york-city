Uber Pickups Analysis (NYC) 🚕
This project performs an exploratory data analysis (EDA) on the Uber New York City dataset, covering over 4.5 million pickups from April to September 2014. The goal is to uncover hidden patterns in urban mobility, identify peak hours, and analyze the performance of various dispatching bases.

<img width="1011" height="990" alt="image" src="https://github.com/user-attachments/assets/47c8d02d-31d0-4c0b-9473-a9f52ba67f72" />

<img width="1135" height="701" alt="image" src="https://github.com/user-attachments/assets/214d3e48-99b1-435a-9922-95a9f8c58bbe" />

<img width="846" height="547" alt="image" src="https://github.com/user-attachments/assets/04dcb32f-2064-4008-8b5c-d729682b8f5e" />

<img width="1031" height="547" alt="image" src="https://github.com/user-attachments/assets/430cf4d3-91e6-4bec-bfe4-79ad1fbf921a" />


📊 Key Insights
Based on the analysis, the following trends were identified:

Peak Demand: Uber demand in NYC consistently spikes between 4:00 PM and 9:00 PM, aligning with the evening commute and nightlife.

Geographical Hotspots: Pickup density is highest in Manhattan and at major travel hubs like JFK and LaGuardia Airports.

Top Performers: Two bases, B02617 and B02598, dominate the market share, each handling over 1.4 million trips during the period.

Weekly Rhythm: Weekdays show a distinct morning rush (7:00 AM - 9:00 AM), while weekends exhibit sustained high demand late into the night.

🛠️ Tech Stack
Python: Primary programming language.

Pandas: For data cleaning and manipulation.

Matplotlib & Seaborn: For creating density maps, heatmaps, and trend charts.

Kagglehub: For direct dataset integration.

🚀 How to Use
Installation: Ensure you have the necessary libraries:

Bash
pip install pandas matplotlib seaborn kagglehub
Data Loading: Use the kagglehub library to download the raw CSV files.

Preprocessing: Convert the Date/Time column to datetime objects and handle encoding (use latin1) to avoid Unicode errors.

Execution: Run the notebook cells sequentially to generate the visualizations.

📈 Visualizations Included
Density Map: A spatial scatter plot visualizing the "pulse" of NYC through latitude and longitude.

Demand Heatmap: A cross-analysis of "Day of Week" vs. "Hour of Day" to find the busiest times.

Base Comparison: A bar chart and line graph comparing the trip volumes of the major Uber dispatching bases.

Future Work
Planned improvements include merging this data with NYC Weather datasets to analyze how rain or snow affects Uber's surge pricing and demand.# uber-pickups-in-new-york-city
uber-pickups-in-new-york-city
