# Airbnb-Python-EDA
# 🏙️ New York Airbnb EDA Project (2024)

This project performs a detailed **Exploratory Data Analysis (EDA)** on the **New York Airbnb 2024 dataset**, containing over 20,000 listings. The analysis helps uncover patterns in price, location, room type, and availability, while demonstrating real-world data cleaning and visualization techniques.

---

## 🚀 Overview

In this project, we use Python libraries like **Pandas**, **NumPy**, **Seaborn**, and **Matplotlib** to:
- Clean and preprocess raw Airbnb data
- Visualize key relationships
- Understand pricing trends
- Identify outliers and insights that matter to hosts, guests, and analysts

---

## 🔍 Topics Covered

### ✅ 1. Data Cleaning and Preprocessing
- Handling missing values
- Removing invalid or inconsistent entries
- Type conversion (e.g., converting IDs or codes to strings)

### 📊 2. Summary Statistics & Correlation Analysis
- Descriptive statistics using `df.describe()`
- Correlation matrix and heatmap to study relationships among numerical variables

### 📈 3. Visualizations
- **Histograms** to explore price distributions
- **Pairplots** to study relationships between price, reviews, nights, and availability
- **Bar plots** to compare average prices across neighbourhoods and room types
- **Boxplots** for identifying outliers and analyzing price spread

### 🗺️ 4. Neighbourhood & Price Analysis
- Price variation by borough (`neighbourhood_group`)
- Geographic trends using latitude and longitude

### 🏠 5. Room Type and Availability Insights
- Distribution of listings by `room_type`
- Year-round availability using `availability_365`
- Price per bed calculations

### 🚫 6. Outlier Detection and Advanced Filtering
- Filtering extreme price values
- Using thresholds to clean and refine analysis
- Scatter plots to visualize outliers and trends

---

## 🛠️ Tools Used

| Library     | Purpose                                |
|-------------|----------------------------------------|
| **Pandas**  | Data manipulation and cleaning         |
| **NumPy**   | Numeric operations and transformations |
| **Matplotlib** | Static plotting and customization  |
| **Seaborn** | High-level statistical visualizations  |

---

## 📁 Dataset

- **Source**: [Inside Airbnb - NYC Listings (2024)](http://insideairbnb.com/get-the-data/)
- Contains over **20,000+ records**
- Features include: price, neighbourhood, room type, reviews, availability, etc.

