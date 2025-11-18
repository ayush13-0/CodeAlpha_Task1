# 🧾 Hybrid Data Extraction & Analytics Projects
Comparative Product Insights from E-Commerce & Food Domains

(BooksToScrape Web Scraping + OpenFoodFacts API)

🚀 Project Overview

This project performs hybrid data extraction, cleaning, and analytics using two completely different data sources:
- BooksToScrape → Web scraping (E-Commerce data)
- OpenFoodFacts API → API-based product extraction (Food & Nutrition data)

The goal is to compare data patterns, visualize insights, and demonstrate scalable data engineering techniques using Python.

🎯 Objectives:
- Scrape structured book product data (title, price, rating, availability, etc.)
- Fetch food product data via OpenFoodFacts REST API
- Clean, preprocess, and merge multi-domain datasets
- Perform exploratory data analysis (EDA) and generate visual insights
- Build a reproducible and well-organized data pipeline

🧰 Tech Stack & Libraries:
- Python
- Requests
- BeautifulSoup
- Pandas
- Matplotlib
- Seaborn
- JSON
- Regex

🧩 Workflow Summary
1️⃣ Data Extraction
📘 BooksToScrape (Web Scraping)
- Fetch book titles, price, stock status, rating
- Create structured tabular dataset

🍎 OpenFoodFacts API (JSON API)
- Query packaged food items
- Extract nutrition fields: energy, fat, sugar, etc.
- Standardize and load into DataFrame

🧹 2️⃣ Data Cleaning & Preparation
- Remove nulls, duplicates
- Convert string values to numeric
- Normalize price, nutrition fields
- Filter products for meaningful comparisons

📊 3️⃣ Visualizations & Analytics
📘 Books Data
- Price distribution
- Boxplot for average book price & outliers

🍏 Food Data
- Energy vs sugar scatter plot
- Top 10 countries by product count

🔍 4️⃣ Key Insights: 
- Books show a moderate price distribution with visible outliers
- Certain food categories show strong correlation between sugar & energy
- Countries differ widely in OpenFoodFacts product contributions
- Hybrid data integration demonstrates powerful cross-domain analytics

🗂 Project Structure
├── Hybrid_Data_Extraction_Analytics_Project.ipynb
├── README.md

👨‍💻 Developed By
Ayush
Data Science & Analytics | Machine Learning | Web Scraping & APIs
- 🔗 GitHub: https://github.com/ayush13-0
- 🔗 LinkedIn: https://www.linkedin.com/in/ayush130

📜 License
- This project is licensed under the **MIT License**.
