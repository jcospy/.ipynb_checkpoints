## Car Sales Dataset Analysis
# Overview
This project involves analyzing a dataset of car sales to derive insights related to car brands, models, and various features such as price, fuel efficiency, engine size, and resale value. Several exploratory data analysis techniques were applied to understand patterns in the data, clean it, and visualize key findings.

# Steps Followed in the Analysis
1. Importing the Dataset and Initial Inspection
The dataset was imported using the Pandas library.
Displayed the first 5 rows to understand the structure of the data.
Displayed the last 10 rows to examine the end of the dataset.
Used the shape method to find out that the dataset contains X rows and Y columns.
The info() method was used to get a detailed summary of the dataset, including data types and non-null counts for each column.
2. Data Types and Missing Values
Data types of each column were checked for appropriateness. Some columns required adjustments, for example:
Corrected data types where needed (e.g., ensuring numerical columns were properly formatted).
Missing values were checked:
Filled missing values in the year_resale_value column with the column's mean value.
Dropped rows that contained missing values in any other columns after this step.
3. Cleaning Column Names
Cleaned the name of the __year_resale_value column by removing the leading underscores.
4. Descriptive Statistics
Performed descriptive statistics on numerical columns, including the mean, median, and standard deviation. The data revealed:
Some significant variations in sales and horsepower across different car models and manufacturers.
Insights into price distributions and fuel efficiency variations.
5. Handling Duplicates
Checked for duplicate rows in the dataset.
Duplicates, if any, were removed to ensure data integrity.
# Specific Analysis Performed
1. Most Common Car Brand
Identified the most common car brand using the value_counts() method, which revealed which manufacturer had the highest representation in the dataset.
2. Manufacturers with Highest and Lowest Average Sales Volume
Grouped the data by car manufacturer and calculated the average sales volume.
Identified which manufacturer had the highest and lowest average sales volumes.
3. Car Price Distribution
A histogram was plotted to visualize the distribution of car prices, revealing the general price range and possible skewness in the data.
4. Correlation Matrix
A correlation matrix was plotted to understand relationships between numerical variables, such as how price, engine size, and fuel efficiency correlate with each other.
5. Histogram of Car Prices
A histogram was plotted using Matplotlib to visualize how car prices are distributed in the dataset.
6. Relationship Between Price and Latest Launch Year
A scatter plot was created to analyze the relationship between car price and the latest launch year of models, allowing us to explore any potential trends over time.
7. Grouping by Manufacturer
Grouped cars by manufacturers and calculated their average price and fuel efficiency to compare different brands in terms of cost and fuel economy.
8. Visualizing Popular Car Brands
A bar chart was plotted to visualize the most popular car brands in terms of the number of cars in the dataset.
9. Car Model with Highest Resale Value
Identified the car model with the highest resale value compared to its initial price by calculating the resale value as a percentage of the initial price.
10. Top 3 Fuel-Efficient Cars with Large Engines
Filtered cars with engine sizes above 2.5 liters and identified the top 3 most fuel-efficient cars among them.
11. Lexus Model with Highest Horsepower
Filtered Lexus models and found the one with the highest horsepower.
# Libraries Used
Pandas: For data manipulation and cleaning.
Matplotlib: For visualizing the data through plots and charts.
Seaborn: For advanced visualization, such as correlation matrices.
# Conclusion
This analysis provided valuable insights into the car sales dataset, such as identifying popular brands, understanding price distribution, and analyzing the relationship between various features like engine size, horsepower, and fuel efficiency. Through data cleaning and visualization, several key trends were uncovered, aiding in a better understanding of the automotive market.
