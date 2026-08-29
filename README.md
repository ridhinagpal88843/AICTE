Car Market Trends Analysis : Car Dekho Data
Exploratory data analysis of 301 used car listings from Car Dekho, uncovering the factors that drive resale price built with Python in Google Colab.


Project Description
This project analyzes real used-car listing data to understand how a car's age, mileage, fuel type, seller type, and transmission relate to its resale value. It covers the full EDA workflow: data cleaning, outlier detection and treatment (IQR method), and visual analysis to surface meaningful, data backed market insights.


Problem Statement
Used car buyers and sellers have no simple, data-driven way to judge whether a price is fair. Resale value depends on many interacting factors, making manual judgment unreliable. This project analyzes real Car Dekho listings to uncover which factors actually drive price, and by how much.


Dataset
Source: Car Dekho used car listings
Rows: 301 listings
Columns: Car_Name, Year, Selling_Price, Present_Price, Kms_Driven, Fuel_Type, Seller_Type, Transmission, Owner
No missing values in the raw dataset



Tech Stack
Python	Core language
Pandas & NumPy :	Data loading, cleaning, IQR-based outlier treatment
Matplotlib & Seaborn	Histograms, boxplots, scatter, violin, and bar plot visualizations
Google Colab for Development and execution environment


Analysis Workflow
Explore — shape, dtypes, summary statistics, missing-value check
Feature engineering — derive Car_Age from Year
Outlier detection — boxplots on price and mileage columns
Outlier treatment — IQR-based capping on Kms_Driven and Selling_Price
Visualization — distributions, relationships, and group comparisons
Insights — group-level summaries by seller type, fuel type, and car age
