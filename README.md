🦈 Shark Tank India Season 1 – Data Analysis & Visualization
📌 Introduction
This project explores detailed insights from Season 1 of Shark Tank India, a business reality TV show where entrepreneurs pitch their startups to a panel of investors ("sharks") in exchange for funding. The dataset contains 117 pitches and rich metadata about the asks, deals, equity, and investor participation.

The analysis is conducted using Python, primarily with Pandas, NumPy, Matplotlib, and Seaborn in a Jupyter Notebook environment. The goal is to uncover patterns in investment behavior, episode-wise performance, and individual shark involvement.

🧾 Dataset Description
The dataset contains 28 columns and includes the following key information:

Column Name	Description
brand_name	Startup's name
idea	Brief about the product/service
pitcher_ask_amount	Amount asked by the startup (in lakhs)
ask_equity	Equity % the startup is willing to give
deal	1 if deal happened, 0 otherwise
deal_amount	Final deal amount offered by sharks
deal_equity	Final equity given by startup
deal_valuation	Final valuation as per the deal
amount_per_shark	Average amount invested per shark
equity_per_shark	Average equity per shark
total_sharks_invested	Count of sharks invested in that pitch
ashneer_deal, anupam_deal, ...	1/0 if the respective shark invested
ashneer_present, anupam_present, ...	1/0 if the shark was present in the episode

🧰 Tools & Libraries Used
Python – Core programming language

Pandas – Data reading, wrangling, and analysis

NumPy – Numeric operations

Matplotlib & Seaborn – Visualizations and graphs

Jupyter Notebook – Interactive development

🧪 Data Preparation & Cleaning
Imported and read the CSV file using pandas.read_csv()

Used .info() and .describe() to understand column types and statistical distributions

Checked for missing/null values using .isnull().sum()

Cleaned and transformed data using .fillna() and grouping techniques

📊 Exploratory Data Analysis (EDA)
✅ Deals Overview
65 successful deals, 52 rejected pitches.

Created pie charts to visualize the percentage distribution of deal outcomes.

📺 Best Performing Episodes
Top episodes with most deals: Episode 1, 15, 21, 33 (each had 3 deals).

Most expensive episodes: Episode 17 had ₹280 lakhs, Episode 13 had ₹255 lakhs in investments.

💰 Investor-Wise Analysis
🧍 Ashneer Grover
Deals: 8

Invested: ₹494.33 lakhs

Equity Taken: 93.25%

🧍 Anupam Mittal
Deals: 24

Invested: ₹533.83 lakhs

Equity Taken: 166.35%

🧍 Aman Gupta
Deals: 28

Invested: ₹887.5 lakhs

Equity Taken: 160.26%

🧍 Namita Thapar
Deals: 22

Invested: ₹648.33 lakhs

Equity Taken: 134.78%

🧍 Vineeta Singh
Deals: 15

Invested: ₹328.33 lakhs

Equity Taken: 131.53%

🧍 Peyush Bansal
Deals: 20

Invested: ₹719.66 lakhs

Equity Taken: 315.85%

🧍 Ghazal Alagh
Deals: 5

Invested: ₹130.0 lakhs

Equity Taken: 46.7%

🤝 Investor Team-Ups
Identified and visualized how many deals had 2, 3, 4, or even all 5 sharks investing together.

Created bar plots and histograms to represent total sharks teamed up in each pitch.

⚖️ No-Bargain Deals
Found startups that got exactly what they asked for (same amount and equity).

Example: BluePine Industries received ₹50L for 10% without any negotiation.

📈 Visualizations
Pie Charts: Deal vs. no deal percentage

Bar Charts: Episode-wise total investment, shark-wise investment count

Swarm Plots: Deal frequency across episodes

Histograms: Number of sharks involved in each investment

Grouped Aggregations: Mean, max, and sum values by episode and investor

🔍 Interesting Observations
Many successful deals had multiple sharks investing, which increased the deal valuation.

Sharks like Aman, Peyush, and Anupam showed more investment interest than others.

Some episodes had large investments but fewer deals, highlighting high-value startups.

Most startups asked for between ₹40-80 lakhs and offered 5-15% equity.

A few outliers asked for very low equity (0.25%) or had unusual valuations.

✅ Conclusion
This analysis highlights how data from a reality show like Shark Tank can provide rich insights into investor behavior, deal-making trends, and startup strategies. It serves as a strong example of:

Practical data analysis

Visual storytelling

Business intelligence using Python

Whether you're a fan of Shark Tank or a data science enthusiast, this project demonstrates how structured analysis can unlock real-world insights.

