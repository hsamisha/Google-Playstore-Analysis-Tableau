# Google Play Store Analysis Dashboard – Tableau

## Project Overview

The **Google Play Store Analysis Dashboard** is an interactive data analytics project developed using **Tableau** and **Python**.

The project analyzes Google Play Store application data to understand app distribution, ratings, reviews, installations, pricing, app size, application types, and content categories.

The analysis is presented through an interactive Tableau dashboard containing KPIs, charts, filters, and multiple analytical pages.

## Objective

The main objectives of this project are to:

- Analyze the distribution of applications across different categories.
- Understand application ratings and review patterns.
- Analyze installation and user engagement patterns.
- Compare free and paid applications.
- Examine application pricing and size.
- Identify categories and applications with strong user engagement.
- Analyze application performance across different categories.
- Present the results through an interactive Tableau dashboard.
- Generate meaningful insights from the dataset.

## Dataset Description

The project uses the **Google Play Store Apps dataset**.

Important fields include:

- App
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Current Version
- Android Version

The project also includes the **Google Play Store User Reviews dataset**, which can be used for additional review-level analysis.

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Tableau
- GitHub
- CSV datasets

## Approach / Methodology

### 1. Data Collection

The Google Play Store datasets were collected and loaded for analysis.

### 2. Data Cleaning

The data was checked and prepared by handling:

- Missing values
- Duplicate application records
- Incorrect data types
- Non-numeric values
- Installation formatting
- Price formatting
- Application size values

### 3. Exploratory Data Analysis

EDA was performed to analyze:

- App distribution by category
- Rating distribution
- Review patterns
- Installation patterns
- Free vs paid applications
- Pricing distribution
- App-size patterns
- Content-rating distribution
- Category-level performance

### 4. Data Visualization

Charts were created to identify important trends, relationships, and patterns in the dataset.

### 5. Tableau Dashboard Development

The cleaned dataset was used to develop an interactive Tableau dashboard containing KPIs, charts, filters, and multiple analytical pages.

### 6. Insight Generation

The analysis was used to identify important trends, patterns, and observations from the Google Play Store dataset.

## Analysis & Key Findings

### App Category Analysis

The dashboard analyzes application distribution across different Google Play Store categories.

### Rating Analysis

Application ratings are analyzed to understand user rating patterns and category-level differences.

### Installation & Review Analysis

Installation and review counts are analyzed as indicators of application reach and user engagement.

### Free vs Paid Analysis

The project compares free and paid applications based on pricing, installations, ratings, and other performance indicators.

### App Size Analysis

Application size is analyzed to understand size distribution and differences across applications and categories.

## Key Insights

Based on the analysis:

- The dataset contains applications across a wide range of categories.
- Free applications represent the majority of applications.
- Application ratings provide an indication of user satisfaction.
- Reviews and installations provide useful indicators of user engagement and application reach.
- Installation volume varies considerably across application categories.
- Popular applications can have significantly higher installation and review volumes.
- Free and paid applications show differences in availability and pricing patterns.
- Installation volume and rating should be considered together when evaluating application performance.

## Dashboard Overview

The Tableau project contains three main dashboards.

### Dashboard 1 – Executive Overview

This dashboard provides a high-level summary of the Google Play Store dataset.

It includes:

- Average Rating
- Total Apps
- Total Installs
- Apps by Category
- Top Applications by Installs
- Average Rating by Category
- Free vs Paid Applications

<img width="1574" height="809" alt="image" src="https://github.com/user-attachments/assets/3326b61e-192f-420f-82d6-a8ea19615bc1" />


### Dashboard 2 – App Performance

This dashboard focuses on application performance and user engagement.

It includes:

- Installation Performance
- Review Volume
- Rating Patterns
- Category Comparisons
- Top Performing Applications

<img width="1570" height="837" alt="image" src="https://github.com/user-attachments/assets/3efb02b0-e5d1-40ac-a48e-ff53b3099073" />


### Dashboard 3 – Pricing and App Size

This dashboard focuses on pricing and application size.

It includes:

- Free vs Paid Applications
- Application Pricing
- App Size Distribution
- Price and Performance Patterns
- Category-Level Pricing Differences

<img width="1570" height="837" alt="image" src="https://github.com/user-attachments/assets/327dc278-643c-401f-8666-389b2df78f2c" />


## Key Performance Indicators

| KPI | Description |
|---|---|
| Total Apps | Total number of applications analyzed |
| Average Rating | Average rating of applications |
| Total Installs | Total installation volume |
| Total Reviews | Total review volume |
| Free Apps | Number of free applications |
| Paid Apps | Number of paid applications |

## Recommendations

Based on the analysis:

- Monitor both installation volume and ratings when evaluating application performance.
- Analyze high-performing categories to understand market demand.
- Monitor reviews and ratings to understand user engagement.
- Consider category demand when evaluating pricing strategies.
- Consider application size during application development.
- Use user feedback and review patterns to identify opportunities for improvement.
- Regularly monitor application performance metrics.

## Conclusion

The **Google Play Store Analysis Dashboard** provides an interactive view of application-market patterns using **Tableau**.

The project analyzes application categories, ratings, reviews, installations, pricing, application types, and app sizes to identify meaningful trends and observations.

By combining data cleaning, exploratory data analysis, visualization, and Tableau dashboard development, the project demonstrates practical skills in data analytics and business intelligence.

The interactive dashboard makes the analysis easier to explore and communicate to users and stakeholders.

**Key Insights Cell for the EDA Notebook**

Add the following as the final cell of the EDA notebook after all analysis and visualizations:

print("KEY INSIGHTS FROM GOOGLE PLAY STORE EDA")
print("-" * 50)

print(f"1. The dataset contains approximately 10,841 app records before project-specific cleaning.")
print(f"2. The dataset covers 34 application categories.")
print(f"3. Free apps account for approximately 92.6% of the records, while paid apps account for approximately 7.4%.")
print(f"4. The overall average app rating is approximately 4.19.")
print(f"5. GAME has the highest total installation volume among the categories.")
print(f"6. Google News has one of the highest recorded installation values in the dataset.")
print(f"7. 1.9 has the highest average category rating at approximately 19.00.")
print("8. Installation volume and review count provide useful indicators of app reach and user engagement.")
print("9. Free and paid apps show different market and pricing patterns that can be explored for product strategy.")
print("10. The findings can support decisions related to app development, pricing, user engagement, and category strategy.")
