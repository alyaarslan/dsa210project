# DSA210 PROJECT
The term project given by DSA-210 Course in 2024-2025 Spring at Sabancı University.

# Outdoor Time and Sleep Quality Analysis
**Author:** Alya Ayşe Arslan

## Motivation  
In the digital age, us humans spending extended periods indoors and engaging in online activities has become increasingly common. While this shift in lifestyle has been widely normalized, its effects on sleep quality remain uncertain. This study aims to examine the correlation between time spent outdoors and sleep quality by analyzing personal movement data from Google Timeline and sleep metrics from Samsung Health. Google Timeline records location and movement patterns using GPS, allowing for an accurate measure of outdoor activity duration. Samsung Health provides detailed sleep data, including total sleep duration, REM cycles, light and deep sleep stages, and physical and psychological recovery metrics. The analysis will use data spanning from July 2024 to September 2024, covering a 3 month period. By exploring this correlation, the study aims to get a better understanding of how daily activity levels influence sleep quality.



## Tools  
- **Jupyter Notebook (Python IDE):** Interactive data analysis & visualization.
- **Pandas:** For handling structured data (CSV, JSON).
- **json:** To parse and extract Google Timeline JSON data.
- **Matplotlib:** For line plots, bar charts.
- **Seaborn:** For heatmaps, regression plots.
- **Numpy:** For numerical computations.  
- **Scipy:** For analyzing the relationship between variables in a statistical manner.
- **Google Takeout:** For importing and analyzing Google Timeline data.
- **Samsung Health App:** For importing and analyzing sleep quality data.


## Data Sources  
-This project uses two different sources for personal data tracking to analyze the relationship between outdoor activity and sleep quality. By comparing these data sources, the analysis aims to uncover patterns and correlations between time spent outside and various sleep metrics. This approach provides an understanding of how daily activity levels influence rest and recovery. The data sources include:

- **Google Timeline Data:**  
  - Extracted using Google Takeout.  
  - Tracks movement patterns, locations, and time spent in different places.
  - Used to calculate total outdoor time per day. 

- **Samsung Health Sleep Data:**  
  - Exported from the Samsung Health app. 
  - Includes sleep duration, sleep cycles (REM, deep, light sleep), and recovery metrics.
  - Used to assess the impact of outdoor activity on sleep quality.

- **Time Period:**  
  - The dataset spans from July 2024 to September 2024, covering several months to observe potential trends and correlations. 


## Methodology  
1. **Exploratory Data Analysis (EDA):**  
   - Examine daily outdoor activity levels and sleep patterns.
   - Investigate potential trends between time spent outside and variations in sleep quality. 

2. **Statistical Analysis:**  
   - Apply correlation and regression models to assess the relationship between outdoor activity and sleep quality. 
   - Determine whether increased outdoor time contributes to improved rest and recovery.

3. **Visualization:**  
   - Develop clear and informative charts to illustrate key findings.
   - Use visual representations to highlight trends and potential correlations.
