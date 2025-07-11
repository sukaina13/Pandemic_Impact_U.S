# Pandemic_Impact_U.S

### Overview

This project analyzes the economic impact of the COVID-19 pandemic on employment and GDP trends in the United States. Using public datasets, I investigated pre- and post-lockdown patterns to visualize how the economy responded to the crisis and how it recovered over time.
The primary objective was to understand and quantify the downturn during the pandemic and identify early signs of recovery, while also learning best practices for working with time series data.

### Motivation

COVID-19 disrupted global economies in unprecedented ways. In the U.S., employment rates and GDP dropped significantly in 2020. This project explores the extent of these changes using real economic data and demonstrates how data science can help visualize and interpret large-scale economic shocks.

###  Project Goals
Analyze trends in U.S. employment and GDP from pre-pandemic to post-lockdown periods
Identify significant shifts and recovery patterns
Understand challenges in working with multiple time series sources
Improve skills in data cleaning, merging, and visualization

### Dataset Sources

Employment Data: U.S. Bureau of Labor Statistics (BLS)
GDP Data: U.S. Bureau of Economic Analysis (BEA)
Note: Due to different update frequencies and structures, aligning the datasets was a key preprocessing step.

### Tools Used

Python (Pandas, NumPy, Matplotlib, Seaborn)
Jupyter Notebook
Git/GitHub for version control

### Key Findings

Employment and GDP both saw steep declines in Q2 2020, directly following the initial lockdown.
Visualizations revealed synchronized drops across sectors, with slow but visible recovery by early 2021.
Timeframe mismatches across datasets created analytical challenges, highlighting the importance of careful alignment in time series analysis.

 
 ### Challenges Faced

Dataset alignment: Employment data was monthly; GDP data was quarterly.
Incomplete values and missing metadata required thoughtful cleaning and interpolation.
Avoiding misleading visualizations when comparing trends of different temporal resolutions.


### Future Improvements

Include industry-specific employment trends for deeper insights
Incorporate additional economic indicators (e.g., consumer spending, inflation)
Build an interactive dashboard using Plotly or Streamlit for real-time analysis

License: This project is for educational purposes and may use publicly available datasets.
Always cite original data sources when publishing or sharing insights.
