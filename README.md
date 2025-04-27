# 📦 E-Commerce Pricing Trend Analysis
This project focuses on monitoring pricing trends across major e-commerce platforms to analyze competitor pricing strategies, identify market trends, and evaluate promotional activities. By scraping product pricing data from different platforms, the project aims to provide insights into competitor strategies and price fluctuations over time.

Presentation Video - https://youtu.be/q6kvtRPQYh4

Questionnaire Video - https://youtu.be/8sb1a38kMXc

Kaggle Dataset Link - https://www.kaggle.com/datasets/manishkc06/electronics-product-pricing-dataset/data

🎯 Objectives
Scrape real-time product pricing data from Amazon and Paytm Mall.

Merge it with existing Kaggle historical electronics data.

Clean and standardize the dataset for accurate analysis.

Perform competitor analysis to compare pricing strategies.

Visualize insights through an interactive Power BI dashboard.

🛠 Technologies Used

Technology	Purpose
Python	Web scraping, data cleaning
Selenium	Dynamic website scraping
Pandas	Data wrangling and cleaning
Power BI	Interactive dashboard creation
Excel/CSV	Data storage and export
Git/GitHub	Version control and collaboration
📂 Dataset Sources
amazon_electronics.csv — Scraped from Amazon

paytm_electronics.csv — Scraped from Paytm Mall

electronics_products_pricing.csv — Kaggle dataset

combined_cleaned_electronics.csv — Final merged, cleaned dataset used for analysis

🧹 Data Cleaning Steps
Standardized product names (removed special characters, redundant texts).

Normalized price fields into a consistent INR format.

Handled missing values by appropriate imputation or removal.

Removed duplicate entries.

Removed price outliers using the IQR (Interquartile Range) method.

🏆 Key Features
Competitor Price Comparison: See how different platforms price the same product.

Promotion Analysis: Understand pricing strategies during big events like Black Friday or Diwali sales.

Category Trends: Explore pricing behavior in smartphones, laptops, TVs, etc.

Price Leadership Detection: Identify which platform leads or matches competitor prices.

Interactive Dashboard: Fully interactive and filterable Power BI dashboard showing trends and insights.

📈 Power BI Dashboard Highlights
Product Price Trends over Time

Platform-wise Pricing Comparison

Top Discounted Products Visualization

Category-wise Price Distribution

Promotion Event Impact Analysis

💡 Insights Gained
Amazon typically prices more aggressively during major sale events compared to Paytm.

Smartphones and laptops experience the highest discount percentages.

Platforms tend to quickly match competitor price cuts during promotional seasons.

Pricing differences shrink during competitive sale periods, indicating a race to bottom pricing.

🚀 Future Improvements
Automate live scraping at regular intervals (e.g., daily).

Expand analysis to include Flipkart, Croma, Reliance Digital.

Implement machine learning models to predict future price drops.

Build a web dashboard using Streamlit for real-time monitoring.

🙌 Acknowledgements
Kaggle Community for the base electronics dataset.

📣 Thank you for exploring this project!
Feel free to reach out if you have any suggestions, feedback, or ideas to enhance it further!
E-mail - vishalkapoor9803@gmail.com
