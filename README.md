<h1>Real Estate Market Analysis – WorldQuant University Data Science Project</h1>

<div class="section">
<h2>Project Overview</h2>

<p><strong>Project Name:</strong> Real Estate Price Analysis</p>
<p><strong>Institution:</strong> WorldQuant University – Applied Data Science Lab</p>
<p><strong>Objective:</strong> Analyze real estate datasets to determine whether <strong>property size or location has a stronger influence on property prices.</strong></p>

<p>
This project analyzes over <strong>21,000 real estate listings</strong> sourced from Properati.com.
Using Python and data science techniques, the project investigates patterns in property prices and evaluates how factors such as <strong>property size, geographic location, and regional differences</strong> influence housing markets.
</p>

<p>
The project demonstrates the full <strong>data science workflow</strong> including data cleaning, transformation, exploratory data analysis, visualization, and correlation analysis.
</p>

</div>

<div class="section">

<h2>Business Context & Research Question</h2>

<p>
Real estate markets are influenced by multiple factors including location, property size, economic activity, and regional demand.
Understanding these factors helps investors, developers, and analysts make better decisions.
</p>

<h3>Central Research Question</h3>

<p><strong>Are property prices more strongly influenced by property size or by location?</strong></p>

</div>

<div class="section">

<h2>Data Source</h2>

<p>
Dataset sourced from <strong>Properati.com</strong> containing real estate listings from Brazil.
</p>

<p>The dataset includes information such as:</p>

<ul>
<li>Property price</li>
<li>Property size (square meters)</li>
<li>Latitude and longitude</li>
<li>Region and state</li>
<li>Listing details</li>
</ul>

<p><strong>Total dataset size:</strong> 21,000+ property listings</p>

</div>

<div class="section">

<h2>Data Preparation & Cleaning</h2>

<p>The raw dataset contained inconsistencies that required preprocessing before analysis.</p>

<h3>Data Cleaning Steps</h3>

<ol>
<li>Imported CSV datasets into pandas DataFrames</li>
<li>Removed rows containing missing values</li>
<li>Extracted latitude and longitude from the combined location column</li>
<li>Extracted state names from hierarchical location strings</li>
<li>Converted price values from string format to floating-point numbers</li>
<li>Converted Brazilian Real (BRL) to USD</li>
<li>Removed unnecessary columns</li>
<li>Combined datasets into a single structured DataFrame</li>
</ol>

</div>

<div class="section">

<h2>Exploratory Data Analysis (EDA)</h2>

<p>
Exploratory analysis was conducted to understand patterns within the real estate market.
</p>

<h3>Summary Statistics</h3>

<p>
Descriptive statistics were calculated for the following variables:
</p>

<ul>
<li>Property size (area_m2)</li>
<li>Property price (price_usd)</li>
</ul>

<p>
This helped identify averages, distributions, and variation across the dataset.
</p>

</div>

<div class="section">

<h2>Data Visualizations</h2>

<h3>Distribution of Property Prices</h3>

<p>
A histogram was created to visualize how property prices are distributed.
</p>

<p><strong>Insights:</strong></p>

<ul>
<li>Property prices show significant variation</li>
<li>Most properties fall within a mid-range price band</li>
</ul>

<h3>Distribution of Property Sizes</h3>

<p>
A horizontal boxplot was used to visualize property size distribution.
</p>

<p><strong>Insights:</strong></p>

<ul>
<li>Large variation in property sizes</li>
<li>Presence of potential outliers</li>
</ul>

<h3>Mean Price by Region</h3>

<p>
A bar chart was created to compare the average property price across different Brazilian regions.
</p>

<p><strong>Insights:</strong></p>

<ul>
<li>Some regions consistently show higher property prices</li>
<li>Location significantly influences housing value</li>
</ul>

<h3>Price vs Property Size</h3>

<p>
A scatter plot was used to analyze the relationship between property size and property price.
</p>

<p><strong>Insights:</strong></p>

<ul>
<li>Larger properties generally have higher prices</li>
<li>Price variability indicates that location also plays an important role</li>
</ul>

</div>

<div class="section">

<h2>Correlation Analysis</h2>

<p>
Correlation coefficients were calculated between <strong>property size (area_m2)</strong> and <strong>price (price_usd)</strong> across states in the southern region of Brazil.
</p>

<p>
The analysis showed a <strong>moderate positive correlation</strong>, meaning that larger properties tend to be more expensive, but location also significantly affects property value.
</p>

</div>

<div class="section">

<h2>Key Skills Demonstrated</h2>

<ul>
<li>Python Programming</li>
<li>Data Cleaning</li>
<li>Exploratory Data Analysis (EDA)</li>
<li>Data Visualization</li>
<li>Feature Engineering</li>
<li>Statistical Analysis</li>
<li>Correlation Analysis</li>
<li>Data Storytelling</li>
</ul>

</div>

<div class="section">

<h2>Tools & Technologies</h2>

<table>

<tr>
<th>Tool</th>
<th>Purpose</th>
</tr>

<tr>
<td>Python</td>
<td>Data analysis and programming</td>
</tr>

<tr>
<td>Pandas</td>
<td>Data cleaning and transformation</td>
</tr>

<tr>
<td>Matplotlib</td>
<td>Data visualization</td>
</tr>

<tr>
<td>Jupyter Notebook</td>
<td>Project development environment</td>
</tr>

<tr>
<td>GitHub</td>
<td>Version control and project hosting</td>
</tr>

</table>

</div>

<div class="section">

<h2>Key Learning Outcome</h2>

<p>
One of the most important lessons from this project was learning how to <strong>connect domain knowledge with technical data science skills.</strong>
</p>

<p>
Coming from a tourism background, understanding how <strong>location influences economic value</strong> helped interpret patterns in real estate pricing.
</p>

<p>
This experience reinforced a key principle in data science:
</p>

<p><strong>Domain knowledge + technical skills = deeper insights.</strong></p>

<p>
Rather than abandoning previous knowledge, this project demonstrated how existing expertise can enhance analytical thinking and data storytelling.
</p>

</div>

<div class="section">

<h2>Project Structure</h2>

<pre>
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
└── README.html
</pre>

</div>

<div class="section">

<h2>Future Improvements</h2>

<ul>
<li>Build a machine learning model to predict property prices</li>
<li>Apply regression models for price prediction</li>
<li>Perform geospatial analysis using mapping tools</li>
<li>Create an interactive dashboard using Power BI or Tableau</li>
</ul>

</div>

</body>
</html>
