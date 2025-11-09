# Exploratory-Data-Analysis-of-Smartphone-Pricing-and-Specifications-on-Flipkart
Web Scraping + Exploratory Data Analysis (EDA)

This project performs web scraping and exploratory data analysis (EDA) on smartphone listings from Flipkart. It demonstrates practical data-science skills including data collection, cleaning, feature engineering, visualization, and market insight generation—making it a strong portfolio project for recruiters.

 Project Highlights
 Web Scraping with requests + BeautifulSoup
 Data Cleaning & preprocessing of messy text data
 EDA on pricing, ratings, specifications, and brand performance
 Extracted insights on price–spec relations, brand trends, market segments


 Delivered a clean dataset for further modeling or dashboarding


Technologies Used
Python
pandas, numpy
matplotlib, seaborn
requests, BeautifulSoup
Jupyter Notebook



1. Web Scraping
The dataset was scraped directly from Flipkart mobile listings across multiple pages.
Data Collected:
Smartphone Name
Price (₹)
Ratings
RAM, Storage
Processor
Battery
Camera Details

Scraping Features:
Pagination handling
HTML parsing using BeautifulSoup
Fail-safe request headers
Creation of structured dataframe
Export to CSV


2. Data Cleaning
Key cleaning tasks included:
Removing symbols, commas, and converting price & numeric columns
Extracting structured features from text (RAM, Storage, Battery)
Fixing inconsistent brand names
Dropping duplicates
Handling missing values
Ensuring all features are analysis-ready



3. Exploratory Data Analysis (EDA)
Analysis Performed:
Smartphone price distribution
Brand-wise product count
Rating distribution across brands
Relationship between price vs RAM, price vs Storage, price vs Battery
Comparison of budget, mid-range, and flagship phones
Correlation heatmap of numeric features

Visuals Included:
Bar charts
Histograms
Boxplots
Scatterplots
Heatmaps



Key Insights
Budget smartphones dominate the Flipkart marketplace.
Higher RAM & Storage strongly correlate with higher prices.
Some brands offer strong specs at budget pricing, creating value advantage.
Ratings do not always correlate strongly with higher price.
Battery and storage size significantly influence price segmentation.



Conclusion
This project demonstrates a full end-to-end data workflow—from collecting raw data through web scraping to transforming it into meaningful business insights. By cleaning messy real-world data, engineering usable features, and performing deep exploratory analysis, the project highlights your ability to understand market behavior, evaluate product trends, and support data-driven decision-making. It reflects practical, industry-oriented skills that are valuable in roles involving analytics, data science, and pricing or product strategy.

Future Improvements
Build a smartphone price prediction ML model
Add customer review scraping + sentiment analysis
Publish an interactive dashboard (Streamlit / PowerBI)
Automate data refresh with a script

