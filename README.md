# data-analysis-ETL
In this repository, you'll find analyses of both yellow taxi data and Amazon sales data.

## 1. ny_yellow_taxi_dataset_2023

### Data Source
The New York taxi data for the year 2023 is sourced from monthly Parquet files, each containing yellow taxi trip records.

### About the Data
Yellow taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemised fares, rate types, payment types, and driver-reported passenger counts.

### Summary of the Project
This PySpark project analyses New York taxi data from the year 2023, focusing on yellow taxi rides. The analysis covers various aspects such as revenue, busiest times, popular locations, statistical fare analysis, payment types, customer satisfaction, trip distances, and more. Visualisations using matplotlib and seaborn are incorporated to enhance the presentation of key insights.

### Dependencies
- PySpark
- Matplotlib
- Seaborn
- Pandas
- Numpy

### Analysis Highlights
1) Total Revenue and Trips for the Year: Calculated the total revenue generated and the total number of trips carried out for the entire year based on the Amazon sales data.
2) Busiest Months, Days, and Hours: Identified and ranked the top 5 busiest months, days, and hours of the year, providing insights into peak activity periods.
3) Popular Pickup and Drop Locations: Explored the most popular pickup and drop locations by analyzing the frequency of each location ID.
4) Fare Amount Statistical Analysis: Conducted a statistical analysis of fare amounts, including minimum, maximum, average, and standard deviation.
5) Preferred Payment Types: Analyzed the distribution of payment types used by customers, highlighting the most preferred payment methods.
6) Average Trip Distance: Calculated and presented the average trip distance covered in the Amazon sales data.
7) Passenger Count Analysis: Explored the distribution of passenger counts, providing insights into the occupancy of vehicles during trips.
8) Vendor Performance Comparison: Compared the performance of different vendors based on the number of trips and revenue generated by each vendor.
9) Customer Satisfaction Analysis Based on Ratings: Examined customer satisfaction by analyzing the distribution of ratings and calculating average ratings.
10) Tip Amount Analysis: Conducted an analysis of tip amounts, including average tip amounts and total tips earned each month.
11) Airport Trip and Airport Fee Analysis: Investigated the number of airport trips and the money spent on airport fees, providing insights into airport-related activities.

These analysis highlights aim to provide a comprehensive overview of key metrics and trends in the Amazon sales data, offering valuable insights for further business understanding and decision-making.

### Results and Visualisations
The project generates visualisations using matplotlib and seaborn, showcasing key insights such as payment type preferences, busiest hours, locations, and more.

---

## 2. amazon-sales-data

### Data Source
The Amazon sales data used in this project is sourced from a CSV file, which can be found in the datasets/ directory. The dataset includes information about various products, such as product ID, name, category, pricing details, ratings, reviews, and more.

### About the Data
The dataset comprises essential information related to Amazon sales, offering insights into product details, customer reviews, and pricing trends. It serves as the foundation for in-depth analysis and exploration to uncover patterns, trends, and valuable information.

### Summary of the Project
This PySpark project focuses on leveraging the power of PySpark for the comprehensive analysis of Amazon sales data. It covers various aspects, including data cleaning, statistical insights, and machine learning for sentiment analysis. The goal is to extract meaningful information, patterns, and trends from the dataset to gain valuable insights into customer behaviour and product performance.

### Dependencies
PySpark
Pandas
Numpy
Scikit-learn

### Analysis Highlights
1) Data Cleaning: Identify and handle duplicates, missing values, and non-numeric characters in the dataset.
2) Statistical Analysis: Derive key statistics for actual price, discounted price, discount percentage, rating, and rating count.
3) Category-wise Distribution: Explore the distribution of products across different categories.
4) Discounted Price Analysis: Investigate the highest and lowest discounted prices, average discounted prices, and correlations between prices and ratings.
5) Top Reviews: Identify the top users with the highest number of reviews.
Sentiment Analysis: Utilize machine learning for sentiment analysis, classifying reviews into positive, negative, or neutral.

### Results 
The analysis results encompass key insights into the Amazon sales data, revealing trends, patterns, and meaningful information about product pricing, user ratings, and customer sentiments. The findings are presented in a structured manner, with statistical summaries provided for a clear understanding of the dataset.

