# 🏙️ Airbnb NYC Data Analysis – EDA Project
### 📌 Project Overview
This project involves performing Exploratory Data Analysis (EDA) on the Airbnb NYC dataset to uncover trends, patterns, and insights about listings, pricing, availability, and customer preferences. The analysis helps in understanding how location, property type, and other factors impact pricing and occupancy.

### 🛠 Tools & Libraries Used
- Python (Data analysis & visualization)
- Pandas (Data cleaning & manipulation)
- NumPy (Numerical operations)
- Matplotlib & Seaborn (Data visualization)
- Jupyter Notebook (Interactive analysis)

### 📂 Dataset Information
- **Dataset Name:** Airbnb NYC Listings Dataset
- **Rows:** ~48,000+ listings
- **Columns:** 16 attributes (host details, room type, price, availability, location, reviews, etc.)
#### Key columns include:
- neighbourhood_group – Manhattan, Brooklyn, Queens, Bronx, Staten Island
- room_type – Entire home/apt, Private room, Shared room
- price – Nightly price of listing
- availability_365 – Number of days available per year
- number_of_reviews – Total reviews received

### 🔍 EDA Process
The analysis followed these key steps:
- Data Cleaning & Preprocessing
- Checked for missing values and duplicates
- Removed outliers (extreme prices, unrealistic availability values)
- Handled incorrect data types
- Univariate Analysis
- Distribution of prices
- Frequency of listings by neighbourhood group and room type
- Bivariate & Multivariate Analysis
- Price variations by neighbourhood group & room type
- Correlation between reviews, availability, and price
- Geospatial Analysis
- Mapping listings using latitude and longitude
- Identifying price hotspots

### 📊 Key Insights
- Manhattan has the highest average prices, but Brooklyn has a large number of moderately priced listings.
- Entire homes/apartments are the most expensive, while shared rooms are the cheapest.
- Certain neighbourhoods show price anomalies, indicating possible luxury or premium listings.
- A large percentage of listings are available year-round, indicating professional hosting activity.

### 📈 Visualizations Included
- Price distribution histograms
- Room type vs price boxplots
- Neighbourhood group comparison bar charts
- Heatmap of correlations
- Geospatial scatter plot of listings across NYC

### 💡 Business Impact
The insights can help:
- Hosts – Price their listings competitively based on neighborhood and property type
- Travelers – Identify affordable locations and property types
- Platform (Airbnb) – Detect unusual pricing or availability patterns
