📊 Mobile Phone Market Data Analysis
📌 Project Overview

This project performs an Exploratory Data Analysis (EDA) on a dataset of 5,000+ smartphone listings from multiple brands including Samsung, Redmi, Oppo, Vivo, Realme, and Apple. The goal is to explore pricing, discounts, ratings, reviews, brand presence, and stock availability to uncover key market insights.

🗂️ Dataset

The dataset contains the following columns:

id – Unique product identifier

title – Smartphone name

brand – Brand name (Samsung, Redmi, etc.)

mrp – Maximum Retail Price

selling_price – Final selling price

discount / discount_amount – Price discount details

key_specs – Important product specifications (RAM, storage, etc.)

warranty – Warranty details

url – Product link

rating – Average customer rating

rating_count – Number of ratings

review_count – Number of reviews

stock – Availability status (In Stock / Out of Stock)

🔎 Key Analysis Performed

✅ Data Cleaning – Removed duplicates, handled missing values, standardized stock column.
✅ Price & Discount Analysis – Compared MRP vs selling price, calculated real savings, analyzed discount trends per brand.
✅ Brand Popularity – Count of phones per brand, top 5 most listed brands.
✅ Ratings & Reviews – Top-rated phones, average rating per brand, correlation between ratings and reviews.
✅ Stock Availability – % of in-stock vs out-of-stock phones per brand.
✅ Value-for-Money Metric – New column = selling_price ÷ rating to find best deals.
✅ Key Specs Insights – Extracted RAM & storage from key_specs to compare prices.

📊 Tools & Libraries Used

Python 3

Pandas → Data cleaning & manipulation




📌 Future Improvements

Build interactive dashboards using Power BI or Tableau.

Apply Machine Learning models to predict pricing or ratings.

Automate data scraping to keep dataset updated.



🚀 How to View the Project

Download the file mobile_analysis.html from this repository.

Open the file in any modern browser (Chrome, Edge, Firefox, etc.).

Explore the full analysis, tables, and interactive visualizations directly.

✅ No need to install Python or Jupyter – everything runs in the browser!
