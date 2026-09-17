Cryptocurrency Market Analysis Dashboard

Project Overview

This project is a cryptocurrency data analysis project developed using
Excel, Python, PostgreSQL, and Power BI. It demonstrates an
end-to-end data analytics workflow, including exploratory data analysis,
data cleaning, statistical analysis, SQL operations, visualization, and
interactive dashboard development.

The project analyzes cryptocurrency market information such as price,
market capitalization, trading volume, and percentage changes.

Tools & Technologies

Microsoft Excel --- Manual exploratory data analysis

Python (Jupyter Notebook / Google Colab) --- Data cleaning,
analysis, statistics, and visualization

PostgreSQL --- Database and SQL operations

Power BI --- Interactive dashboard and data visualization

Python Libraries --- Pandas, NumPy, Matplotlib, Seaborn, SciPy,
and Scikit-learn

Dataset

The cryptocurrency dataset used in the Python analysis initially
contained:

93,486 records

9 original columns

65 unique cryptocurrency names

68 unique cryptocurrency symbols

The main variables include:

Timestamp

Cryptocurrency name

Symbol

Price in USD

24-hour trading volume

Total volume

24-hour percentage change

7-day percentage change

Market capitalization

Project Workflow

Excel --- Exploratory Data Analysis

Excel was used to manually explore the cryptocurrency dataset and
understand its structure before performing deeper analysis.

The Excel component demonstrates:

Dataset inspection

Manual exploratory analysis

Data understanding

Summary analysis

Python --- Data Cleaning and Analysis

Python was used to clean and analyze the cryptocurrency dataset.

Financial fields contained characters such as dollar signs, percentage
signs, commas, and abbreviations including K, M, B, and T. These fields
were converted into numerical values for analysis.

The Python workflow included:

Inspecting dataset dimensions

Checking data types

Identifying missing values

Checking duplicate records

Exploring unique cryptocurrencies

Converting timestamps to datetime

Cleaning financial variables

Converting text-based financial values to numeric values

Descriptive statistical analysis

Correlation analysis

Cryptocurrency market-cap analysis

Bitcoin price trend analysis

Regression analysis

Outlier detection

After cleaning, the analytical dataset contained approximately 93,450
records.

Statistical Analysis

The analysis produced the following descriptive results:

Metric                                         Result

Average Cryptocurrency Price                ~$5,458
Median Cryptocurrency Price                  ~$3.40
Average Market Capitalization      ~$159.18 Billion
Median Market Capitalization        ~$19.18 Billion
Average 24-Hour Trading Volume      ~$10.05 Billion
Average 24-Hour Change                       ~+0.29%
Average 7-Day Change                         ~+2.21%

Key Insights

1. Cryptocurrency Prices Are Highly Dispersed

The average cryptocurrency price was approximately $5,458, while
the median was only around $3.40.

This large difference shows that cryptocurrency prices in the dataset
are highly skewed, with a smaller number of high-priced observations
substantially increasing the average.

2. Market Capitalization Varies Significantly

The analysis showed a large difference between average and median market
capitalization.

Average market capitalization: approximately $159.18 billion

Median market capitalization: approximately $19.18 billion

This indicates that market value is concentrated among larger
cryptocurrencies in the dataset.

3. Trading Activity Differs Across Cryptocurrencies

The average 24-hour trading volume was approximately $10.05
billion.

The wide range of trading-volume observations shows substantial
differences in trading activity across cryptocurrencies.

4. Short-Term Market Performance Changes Considerably

The dataset includes both positive and negative cryptocurrency
movements.

The average:

24-hour change was approximately +0.29%

7-day change was approximately +2.21%

This demonstrates the changing short-term behavior represented in the
cryptocurrency dataset.

5. Price and Market Capitalization Relationship

A regression analysis was performed between cryptocurrency price and
market capitalization.

The model produced an R² value of approximately 0.9712 in the
analyzed dataset, showing a strong fitted relationship between the two
variables within this dataset.

6. Price Outliers

The IQR method was used to identify unusual cryptocurrency price
observations.

Approximately 18,119 observations were identified outside the
calculated IQR price boundaries.

Because cryptocurrencies can naturally have very different nominal
prices, these observations represent statistical outliers and are not
necessarily incorrect records.

PostgreSQL / SQL

PostgreSQL was used to demonstrate database and SQL fundamentals through
a separate sales dataset.

The SQL component includes:

Creating a database

Creating tables

Inserting records

Filtering records using WHERE

Sorting data using ORDER BY

Updating records using UPDATE

Deleting records using DELETE

Aggregating data using GROUP BY

Calculating total and average values

Joining tables using JOIN

This component demonstrates practical knowledge of relational databases
and SQL query operations.

Power BI Interactive Dashboard

Power BI was used to create an interactive cryptocurrency dashboard.

The dashboard contains KPI cards displaying:

Total Coins

Total Market Cap

Average Price

Top Coin by Market Cap

The dashboard also contains visualizations for:

Total Market Cap by Coin

Cryptocurrency Price Trend Over Time

24-Hour Percentage Change

Market Cap vs. 24-Hour Trading Volume

Detailed cryptocurrency data

Interactive slicers allow dashboard users to filter the analysis by:

Cryptocurrency / Coin Name

Date

Market Capitalization

These filters allow users to interactively explore different parts of
the cryptocurrency dataset.

Dashboard Features

The Power BI dashboard includes:

4 KPI cards

Market capitalization comparison

Price trend visualization

24-hour change visualization

Trading-volume and market-cap comparison

Detailed cryptocurrency table

Coin filter

Date filter

Market-cap filter

Skills Demonstrated

This project demonstrates experience with:

Data Analytics

Data Cleaning

Exploratory Data Analysis

Excel

Python

Pandas

Statistical Analysis

Regression Analysis

Outlier Detection

Data Visualization

PostgreSQL

SQL

Relational Databases

Power BI

Interactive Dashboard Development

Data Storytelling

Project Files

Cryptocurrency-Market-Analysis/
│
├── README.md
├── CryptoDashboard.ipynb
├── MANUAL DATA EDA.xlsx
├── SQL Report.docx
└── dashboard.pbix

Author

Hafiz Muhammad Abdul Rehman

Data Analytics Portfolio Project
