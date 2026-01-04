# ETL-Bank-Data-Analysis

Objective:
By working on Banking Data Analysis using Apache Spark, it aims to give hands-on experience in analyzing large-scale banking datasets using PySpark and AWS services. By applying techniques learned in data analytics to clean, transform, and explore banking data, drawing meaningful insights to support financial decision-making. Apart from understanding how big data tools can optimize performance on a single machine and across clusters, you will develop a structured approach to analyzing market capitalization trends, currency conversions, and global banking performance.

Tasks:
- Data Preparation
- Data Cleaning
  - Handling Missing Values
  - Fixing Columns
  - Handling Outliers
- EDA
  - Convert PySpark DataFrame to Pandas DataFrame for visualization
  - Analyze the distribution of market capitalization using a histogram
  - Identify the top 10 banks by market capitalization using a bar chart
  - Visualize the relationship between market capitalization and bank ranking using a scatter plot
  - Use a boxplot to examine the spread and outliers in market capitalization
  - Display the quartile distribution of market capitalization using a violin plot
  - Compute cumulative market share and visualize it with a line plot
  - Categorize banks into market capitalization ranges and analyze their distribution using a bar chart
  - Calculate and display market share distribution of top 10 banks using a pie chart
- Banking Data ETL Querying
  - Perform Advanced Market Capitalization Analysis with Growth Metrics
  - Analyze Market Concentration and Categorize Banks Based on Market Share Tiers
  - Examine Statistical Distribution of Market Capitalization Using Quartile Analysis
  - Conduct Comparative Size Analysis to Classify Banks by Relative Market Size
  - Evaluate Market Growth and Identify Gaps Between Consecutive Banks
  - Assess Market Dominance by Measuring Cumulative Share and Dominance Score
  - Analyze Segment-Wise Bank Performance Based on Market Capitalization Ranges
  - Generate a Comprehensive Performance Dashboard for Bank Rankings and Metrics
- Conclusion
  - Recommendations to track and compare market capitalisation of the top global banks to evaluate competitiveness and dominance
  - Suggestions to use cross-currency analysis (USD, GBP, EUR, INR) for consistent benchmarking of financial institutions across regions
  - Propose continuous monitoring of market share concentration to identify growth opportunities for mid-tier banks
  - Identify potential regions or banking segments for expansion by analysing gaps between tiers of banks and regional trends

Python Libraries Used:
- pyspark==3.5.4
- pandas==2.2.2
- matplotlib.pyplot
- datetime
- logging
- seaborn
