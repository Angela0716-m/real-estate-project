#Real Estate Market Analysis – WorldQuant University Data Science Project
Project Overview
Project Name: Real Estate Price Analysis
Institution: WorldQuant University – Applied Data Science Lab
Objective: Analyze real estate datasets to determine whether property size or location has a stronger influence on property prices.
This project explores 21,000+ real estate listings collected from Properati.com. Using Python and data science techniques, the project investigates patterns in property prices and evaluates how factors such as area, region, and geographic location influence housing markets.
The project demonstrates the full data science workflow, including data cleaning, transformation, exploratory data analysis, visualization, and correlation analysis.
Business Context & Research Question
Real estate markets are influenced by multiple factors including location, property size, economic activity, and regional demand.
Understanding these factors helps:
• Investors evaluate property value
• Developers identify high-demand regions
• Analysts understand housing market trends
• Buyers make informed purchasing decisions
Central Research Question
Are property prices more strongly influenced by property size or by location?
Data Source
Dataset sourced from Properati.com, containing real estate listings from Brazil.
The dataset includes information such as:
• Property price
• Property size (square meters)
• Geographic coordinates
• Region and state
• Listing information
Total dataset size: 21,000+ property listings
Data Preparation & Cleaning
The raw datasets contained several issues that required preprocessing before analysis.
Data Cleaning Steps
Imported CSV datasets into pandas DataFrames
Removed rows containing missing values
Extracted latitude and longitude from combined location column
Extracted state information from hierarchical location strings
Converted price columns from string to float
Standardized currency by converting Brazilian Real to USD
Removed unnecessary columns
Combined datasets into a single structured DataFrame
These steps ensured the dataset was consistent, clean, and ready for analysis.
Exploratory Data Analysis (EDA)
After cleaning the data, exploratory analysis was conducted to understand patterns in the real estate market.
Summary Statistics
Calculated descriptive statistics for:
• Property size (area_m2)
• Property price (price_usd)
This provided insight into average prices, distribution, and variability in the dataset.
Data Visualization
Several visualizations were created to better understand the data.
Distribution of Property Prices
Histogram showing how property prices are distributed across the dataset.
Insights:
• Property prices show significant variation
• Most properties fall within a mid-range price band
Distribution of Property Sizes
Horizontal boxplot visualizing the distribution of property sizes.
Insights:
• Significant variation in property size
• Presence of potential outliers
Mean Price by Region
Bar chart showing the average property price across different Brazilian regions.
Insights:
• Certain regions have consistently higher property prices
• Geographic location plays an important role in pricing
Price vs Property Size
Scatter plot showing the relationship between property area and price.
Insights:
• Larger homes generally tend to have higher prices
• However, price variation suggests location also influences value
Correlation Analysis
Correlation coefficients were calculated between property size (area_m2) and price (price_usd) across states in the southern region of Brazil.
This analysis helped determine:
• Strength of the relationship between size and price
• Regional differences in real estate valuation
Results showed moderate correlation, indicating that while property size affects price, location also plays a major role in determining value.
Key Skills Demonstrated
Python Programming
Data Cleaning
Exploratory Data Analysis (EDA)
Data Visualization
Feature Engineering
Statistical Analysis
Correlation Analysis
Data Storytelling
Tools & Technologies
Tool	Purpose
Python	Data analysis
Pandas	Data cleaning and transformation
Matplotlib	Data visualization
Jupyter Notebook	Project development
GitHub	Version control
Key Learning Outcome
One of the most important lessons from this project was learning how to connect domain knowledge with technical data science skills.
Coming from a tourism background, understanding how location influences economic value helped interpret patterns in real estate pricing.
This project reinforced an important principle in data science:
Domain knowledge + technical skills = better insights.
Rather than abandoning previous academic knowledge, this experience showed how existing knowledge can enhance data analysis and storytelling.
Project Structure
real-estate-analysis
│
├── data
│   ├── brasil-real-estate-1.csv
│   └── brasil-real-estate-2.csv
│
├── notebooks
│   └── real_estate_analysis.ipynb
│
├── images
│   ├── price_distribution.png
│   ├── area_boxplot.png
│   ├── price_by_region.png
│   └── price_vs_area.png
│
└── README.md
Future Improvements
Potential extensions for this project include:
• Building a predictive model for property prices
• Using machine learning regression models
• Adding geospatial analysis with mapping tools
• Creating an interactive dashboard (Power BI or Tableau)
