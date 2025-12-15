<p align="center">
  <img src="https://img.shields.io/badge/Web%20Scraping-BeautifulSoup-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/API-OpenFoodFacts-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Data%20Extraction-Hybrid%20Pipeline-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/EDA-Exploratory%20Data%20Analysis-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Visualization-Matplotlib%20%7C%20Seaborn-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Status-Production%20Ready-success?style=for-the-badge" />
</p>

# 🚀 Project Overview
This project demonstrates a hybrid data extraction and analytics pipeline using two fundamentally different data sources:
- 📘 BooksToScrape — Web scraping (E-Commerce product data)
- 🍎 OpenFoodFacts API — REST API-based extraction (Food & Nutrition data)

The primary goal is to extract, clean, analyze, and visualize multi-domain datasets, showcasing scalable data engineering, exploratory data analysis (EDA), and cross-domain insight generation using Python.

# 🎯 Project Objectives
- Scrape structured book product data (title, price, rating, availability)
- Fetch food & nutrition data using OpenFoodFacts REST API
- Clean, preprocess, and normalize heterogeneous datasets
- Perform exploratory data analysis (EDA) and visual analytic
- Build a reproducible and modular data pipeline

# 🧰 Tech Stack & Libraries
- Programming: Python
- Web Scraping: Requests, BeautifulSoup
- API Handling: REST API, JSON
- Data Processing: Pandas, NumPy
- Visualization: Matplotlib, Seaborn, WordCloud
- Text & NLP Utilities: Regex, NLTK
- ML Utilities: Scikit-Learn (for analytics readiness)

# 🧩 Workflow Summary
**1️⃣ Data Extraction**
# 📘 BooksToScrape (Web Scraping)
- Extract book title, price, availability, rating
- Parse HTML pages using BeautifulSoup
- Store results in structured tabular format

# 🍎 OpenFoodFacts API (JSON API)
- Query packaged food products
**Extract nutrition attributes:**
- Energy
- Fat
- Sugar
- Country of origin
- Convert JSON responses into clean DataFrames

# 🧹 2️⃣ Data Cleaning & Preparation
- Remove null values and duplicates
- Convert string fields to numeric formats
- Normalize prices and nutrition metrics
- Filter products for meaningful analytical comparisons

# 📊 3️⃣ Visualizations & Analytics
**📘 Books Data Analysis**
- Book price distribution
- Boxplots to identify pricing outliers

**🍏 Food Data Analysis**
- Energy vs Sugar correlation scatter plot
- Top contributing countries by product count
- Nutrition-based comparative insights

# 🔍 4️⃣ Key Insights
- Book prices show moderate distribution with identifiable outliers
- Certain food categories reveal strong correlation between sugar and energy
- OpenFoodFacts data highlights significant country-wise contribution differences
- Demonstrates the power of hybrid data integration across domains

# 🗂 Project Structure
<pre>
├── Hybrid_Data_Extraction_Analytics_Project.ipynb
├── README.md </pre>

# 👨‍💻 Developed By
# Ayush
- Data Science & Analytics | Machine Learning | Web Scraping & APIs
- 🔗 GitHub: https://github.com/ayush13-0
- 🔗 LinkedIn: https://www.linkedin.com/in/ayush130

📜 License

This project is licensed under the MIT License.
