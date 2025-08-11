# 🍽 Zomato Data Analysis Using Python

Overview
Understanding customer preferences and restaurant trends is essential for making informed business decisions in the food industry.  
This project analyzes **Zomato’s restaurant dataset** to uncover insights into restaurant types, pricing, ratings, and order preferences.

 Objectives
We aim to answer key business questions such as:
- Do more restaurants provide online delivery compared to offline services?
- Which restaurant types are most favored by the general public?
- What price range do couples prefer for dining out?
- How do ratings differ between online and offline orders?

 Tools & Libraries
- Python
- pandas – Data manipulation
- numpy – Numerical computations
- matplotlib – Data visualization
- seaborn – Statistical plots

 Dataset
- File: 'Zomato-data-.csv'
- Source: [Zomato Restaurant Data] *(Add dataset link here)*
- Key Columns:
  - name – Restaurant name
  - online_order – Whether the restaurant accepts online orders
  - rate – Average rating
  - votes – Number of votes received
  - listed_in(type) – Type of restaurant
  - approx_cost(for two people) – Price range for two people

 Steps & Methodology
1. Data Import
   - Load dataset using Pandas.

2. Data Cleaning
   - Converted `rate` column to float values.
   - Checked for missing/null values (none found).

3. Exploratory Data Analysis
   - Popular restaurant types (`listed_in(type)`)
   - Votes distribution across restaurant types
   - Most voted restaurant
   - Online vs Offline order availability
   - Rating distribution
   - Preferred price range for couples
   - Rating comparison for online vs offline orders
   - Heatmap showing restaurant type vs order mode

4. Visualization
   - Count plots, histograms, boxplots, and heatmaps to interpret results.


 Key Insights
- "Dining restaurants" dominate the market compared to other categories.
- Most couples prefer restaurants with an "approximate cost of ₹300".
- A majority of restaurants "do not accept online orders".
- "Online orders tend to receive higher ratings" compared to offline ones.
- "Cafes" primarily receive online orders, whereas "dining restaurants" see more offline orders.



