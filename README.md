#  Zomato Exploratory Data Analysis (EDA) Project

## 📌 Project Overview
This project focuses on Exploratory Data Analysis (EDA) of Zomato restaurant data using Python. The main goal is to understand restaurant ratings, customer votes, online ordering, table booking, restaurant categories, and approximate dining costs.

The analysis uses Python libraries to explore the dataset and identify useful patterns and insights through visualizations.

## 🎯 Project Objectives
- Analyze restaurant ratings and customer votes.
- Understand online and offline ordering trends.
- Identify restaurants with the highest customer votes.
- Analyze table booking availability.
- Compare average ratings across restaurant types.
- Explore the average cost for two people.
- Understand restaurant category distribution.

## 🛠️ Tools & Technologies
- **Python**
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.
- **Jupyter Notebook** – Project development and analysis.

## 📂 Dataset Information
The project uses `Restaurantdata.csv`.

**Dataset Overview:**
- Total Records: 148
- Total Columns: 7

### Dataset Columns

| Column Name | Description |
|---|---|
| Restaurant Name | Name of the restaurant |
| Online_Order | Online ordering availability |
| Book_Table | Table booking availability |
| Rate | Restaurant rating |
| Votes | Total customer votes |
| Approx_Cost | Approximate cost for two people |
| Listed_In(Type) | Restaurant category |

## 🧹 Data Cleaning & Preparation
The following data-cleaning steps were performed:

1. Converted the `Rate` column from string format to numeric format.
2. Standardized column names into lowercase.
3. Renamed the approximate cost column to `approx_cost`.
4. Checked missing values.
5. Checked duplicate records.
6. Verified column data types.

**Data Quality Results:**
- Missing Values: 0
- Duplicate Records: 0

## 🔍 Exploratory Data Analysis (EDA)

The project explores the following 10 questions:

1. How many customer votes has each restaurant type received?
2. How many restaurants offer table booking?
3. Which five restaurants have the highest number of votes?
4. Is there a relationship between restaurant ratings and customer votes?
5. What is the average rating for each restaurant type?
6. What type of restaurant has the highest number of records?
7. What ratings do restaurants most commonly receive?
8. Which restaurant type has the highest average cost for two people?
9. Which order mode (online or offline) gets better ratings?
10. Which restaurant types have more offline ordering records?

## 📊 Key Findings

### 1. Online Ordering
- 96 restaurants support online ordering.
- 52 restaurants do not support online ordering.

### 2. Table Booking
- 35 restaurants offer table booking.
- 113 restaurants do not offer table booking.
- 76.4% do not offer table booking.

### 3. Top 5 Restaurants by Votes

| Restaurant Name | Votes |
|---|---:|
| Flavour Cafe Diner | 3159 |
| Coastal Kitchen Lounge | 3120 |
| Garden Hot Corner | 3098 |
| Royal Royal Express | 3088 |
| Green Cafe Kitchen | 3084 |

### 4. Restaurant Types by Total Votes

- Other: 38,788
- North Indian: 30,321
- Buffet: 29,270
- Cafes: 28,866
- Delivery: 28,533
- Dining: 27,837
- South Indian: 26,178
- Desserts: 19,898
- Pubs and bars: 13,388

### 5. Highest Average Restaurant Ratings

- Cafes: 3.98
- North Indian: 3.98
- Other: 3.89

### 6. Average Cost for Two People

- Cafes: 718.75
- Pubs and bars: 710
- Delivery: 643.75

Cafes have the highest average cost among the restaurant categories.

### 7. Online vs Offline Ordering
The box plot compares restaurant ratings for online and offline ordering. The median rating appears slightly higher for restaurants supporting online orders.

## 📈 Visualizations
The project includes:
- Pie Chart – Table booking availability.
- Bar Chart – Top 5 restaurants by votes.
- Scatter Plot – Ratings vs customer votes.
- Bar Chart – Average ratings by restaurant type.
- Histogram – Restaurant rating distribution.
- Box Plot – Online ordering vs restaurant ratings.
- Heatmap – Online and offline ordering across restaurant types.

## 📝 Conclusion
This Zomato EDA project provides useful insights into restaurant ratings, customer votes, online ordering, table booking, restaurant categories, and approximate dining costs.

The analysis shows that online ordering is available at more restaurants than offline-only ordering records. Cafes have the highest average rating and average cost for two people among the listed categories.

This project helped develop practical skills in Python, data cleaning, exploratory data analysis, data visualization, and interpreting business data.

## 👨‍💻 Author
  Ankit Kumar

