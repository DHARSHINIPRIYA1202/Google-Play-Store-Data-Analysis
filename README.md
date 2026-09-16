 Google Play Store Data Analysis

Problem Statement:

Analyze App Performance

To analyze Google Play Store app data and understand app performance based on installs, reviews, ratings, categories, and user engagement, in order to identify trends and areas for improvement.

## Project Objective

The objective of this project is to analyze Google Play Store application data and identify:

- Popular app categories
- Highly installed applications
- Apps with high user reviews
- Rating patterns
- Free vs paid applications
- User engagement
- Areas for app improvement

## Project Workflow

Python Web Scraping
        ↓
Data Collection
        ↓
Data Cleaning using Pandas
        ↓
MySQL Database
        ↓
SQL Analysis
        ↓
Power BI Dashboard
        ↓
Business Insights

## Tools & Technologies

- Python
- Pandas
- Google Play Scraper
- MySQL
- SQL
- Power BI
- Jupyter Notebook

## Data Collection

Google Play Store application data was collected using Python and the `google-play-scraper` library.

The collected data contains information such as:

- App Name
- Category
- Rating
- Reviews
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Current Version

## Data Cleaning

The collected dataset was cleaned using Pandas.

The major cleaning steps included:

1. Handling missing values
2. Converting Rating into numeric format
3. Converting Reviews into numeric format
4. Cleaning the Installs column
5. Converting Price into numeric format
6. Converting Last Updated into date format
7. Removing the Android Version column
8. Removing the Size column
9. Checking duplicate records
10. Exporting the cleaned dataset


## MySQL Database

The cleaned data was stored in MySQL.

Database:

`google_play_analysis`

Table:

`google_play_apps`

MySQL was used to store and query the cleaned data before connecting it to Power BI.



## Exploratory Data Analysis

The analysis focused on:

- Apps by Category
- Installs by Category
- Reviews by Category
- Rating Distribution
- Free vs Paid Apps
- Top Apps by Installs
- Top Apps by Reviews
- Rating Quality
- User Engagement

## Key Insights

1. Free vs Paid Apps

Around 98% of the applications are free, while only a small percentage are paid.

Free apps may have a larger user base because users can download and try them without financial risk.

2. Category Analysis

Productivity has one of the highest numbers of applications in the dataset.

This indicates strong competition within the category.

3. Installation Analysis

Communication has the highest installation reach in the category analysis.

This indicates strong demand and user adoption for communication applications.

4. Review Analysis

WhatsApp Messenger has the highest number of reviews in the analyzed dataset.

This indicates very high user activity and engagement.

5. Rating Analysis

Most applications are concentrated in the 4–5 rating range.

However, rating alone should not be used to measure app success because the number of reviews also matters.

6. Quality Analysis

Game and Sports has the highest quality score, while Medical has the lowest quality score in the dashboard analysis.

Medical applications may require stronger focus on accuracy, trust, usability and reliability.

## Power BI Dashboard

The Power BI dashboard provides interactive analysis through:

- KPI Cards
- Bar Charts
- Column Charts
- Tables
- Slicers
- Decomposition Tree
- Navigation Buttons

The dashboard contains seven analytical pages:

1. Dashboard
2. Categories
3. Apps
4. App Details
5. Ratings
6. Installs
7. Reviews

## Business Insights

The analysis helps companies understand:

- Which categories have strong demand
- Which applications have high user reach
- How users engage with applications
- How ratings relate to app popularity
- Where user satisfaction may need improvement
- How free and paid applications differ

##Conclusion

This project demonstrates an end-to-end data analytics workflow starting from web scraping and data cleaning to database storage, analysis and visualization.

The project provided practical experience in Python, Pandas, MySQL, SQL and Power BI and helped convert raw application data into meaningful business insights.

