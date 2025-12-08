<h1>Customer Shopping Dataset – Analytics & Power BI Dashboard</h1>
##📌 Project Overview

This project focuses on analyzing a Customer Shopping Dataset to uncover insights about customer behavior, purchase patterns, product performance, discounts, and location-based trends.
The analysis was completed using Python (Pandas) and visualized through a Power BI interactive dashboard.

The goal of the project is to extract meaningful insights that can support data-driven decisions in marketing, sales strategy, inventory management, and user engagement.

🗂️ Dataset Description
The dataset includes:
- Customer ID
- Gender
- Location
- Item Purchased
- Category
- Purchase Amount (USD)
- Review Rating
- Discount Applied
- Promo Code Used
- Purchase Date
- Last Purchase Date
-- Additional engineered columns:
- days_since_last_purchase
- purchase_month

🧼 Data Cleaning & Preprocessing

Key steps performed:

Converted all date columns to proper datetime format

Handled missing values in date fields

Standardized numeric fields

Created useful derived columns for analysis

Removed invalid or duplicate entries

Ensured category consistency

Performed summary statistics and EDA

📊 Exploratory Data Analysis

The main analysis covered:

Customer Analysis

Gender distribution

Location distribution

Repeat purchase behavior

Product & Category Analysis

Top-selling items

Top categories by revenue

Highest rated products

Products most dependent on discounts

Discount & Promotion Impact

% of purchases using discounts

Most discount-sensitive categories

Effect of promo codes on revenue

Location Insights

Top 5 locations by revenue

Revenue contribution per city

High-value customer concentration

📈 Power BI Dashboard

A fully interactive Power BI dashboard was built to visualize:
🧠 Key Insights

A small number of locations contribute the most revenue

Discounts significantly boost sales for selected categories

Higher review ratings correlate with higher sales

Several products rely heavily on discounting → optimization needed

Loyal customers show short intervals between purchases

🛠️ Tech Stack

Python → Data Cleaning & EDA

Pandas / NumPy / Matplotlib

Power BI → Dashboard & Visualization
🚀 How to Use

Clone the repository

Open the Jupyter notebook to review the analysis

Load the .pbix file in Power BI Desktop

View and interact with the dashboard

Export visuals or integrate into presentations
🤝 Contributing

Pull requests are welcome! Feel free to contribute improvements or new visualizations.

📧 Contact

Author: Vansh Chandan
For questions or collaboration: [Add your email here]
