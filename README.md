**Google Play Store Analysis**

**Project Overview**

This project analyzes Google Play Store application data to understand app distribution, user ratings, reviews, installations, pricing, app size, and content categories. The analysis combines exploratory data analysis with interactive dashboard reporting to identify patterns that can support product, marketing, and app-market decisions.
This project analyzes Google Play Store application data to understand app distribution, user ratings, reviews, installations, pricing, app size, and content categories. The analysis combines exploratory data analysis with interactive dashboard reporting to identify patterns that can support product, marketing, and app-market decisions.

**Objective**

The main objectives of this project are to:

Understand the distribution of apps across categories and types.

Analyze app ratings, reviews, and installation patterns.

Compare free and paid applications.

Examine pricing and app-size patterns.

Identify categories and applications with strong user engagement.

Discover important trends and observations from the dataset.

Present the results through an interactive Tableau dashboard.

**Dataset Description**

The primary dataset is the Google Play Store Apps dataset.

Key fields include:

App – Application name.

Category – Google Play Store application category.

Rating – User rating of the application.

Reviews – Number of user reviews.

Size – Application size.

Installs – Approximate number of installations.

Type – Free or Paid application.

Price – Application price.

Content Rating – Intended audience/content rating.

Genres – Application genre classification.

Last Updated – Date on which the application was last updated.

Current Ver – Current application version.

Android Ver – Required Android version.

A second file, googleplaystore_user_reviews.csv, contains user-review information and can be used to extend the analysis with sentiment and review-level insights.

**Tools & Technologies Used**

Python

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook

Tableau

GitHub

CSV datasets

**Approach / Methodology**

1. Data Collection

The Google Play Store application dataset was loaded from CSV files.

2. Data Cleaning

The data was checked for:

Missing values

Duplicate application records

Incorrect or inconsistent data types

Non-numeric values in rating, reviews, installs, size, and price fields

Formatting issues in installation and price columns

3. Exploratory Data Analysis

EDA was performed to investigate:

App distribution by category

Rating distribution

Review and installation patterns

Free versus paid applications

Pricing distribution

App-size patterns

Content-rating distribution

Category-level performance

4. Visualization

Charts were created to identify trends and relationships between important variables.

5. Dashboard Development

The analysis was transformed into an interactive Tableau dashboard containing KPIs, charts, comparisons, and category-level analysis.

**Analysis & Key Findings**

Based on the available dataset, the following observations were identified:

The dataset contains approximately 10,841 app records before project-specific cleaning and duplicate handling.

There are 34 application categories, showing a broad range of app-market segments.

Free applications represent approximately 92.6% of the records, while paid applications represent approximately 7.4%.

The overall average rating among available rating values is approximately 4.19.

GAME has the highest total installation volume among the categories in the dataset.

Google News is among the applications with the highest recorded installation value in the dataset.

1.9 has the highest average category rating among categories with available rating data, at approximately 19.00.

Installation volume and review count provide useful indicators of application reach and user engagement, but high installation volume does not automatically imply a higher average rating.

The comparison between free and paid applications helps identify differences in market availability and pricing strategies.

These findings should be interpreted together with the visualizations and cleaned dataset used in the final notebook and dashboard.

**Dashboard Overview**

The Tableau dashboard provides an interactive view of the Google Play Store analysis.

**Dashboard 1 – Executive Overview**

The executive dashboard summarizes the major KPIs and overall app-market patterns, including:

Average Rating

Total Apps

Total Installs

Apps by Category

Top Applications by Installs

Average Rating by Category

Free versus Paid Applications
<img width="1564" height="810" alt="image" src="https://github.com/user-attachments/assets/09c9ad9a-9e17-422f-90ae-17ee8c3b08c8" />


**Dashboard 2 – App Performance**

This dashboard focuses on application performance and user engagement through metrics such as:

Installation performance

Review volume

Rating patterns

Category comparisons

Top-performing applications
<img width="1566" height="834" alt="image" src="https://github.com/user-attachments/assets/6699abe4-e8d3-4786-baad-a5066d3d924a" />


**Dashboard 3 – Pricing and App Size**

This dashboard examines:

Free versus paid applications

Application pricing

App-size distribution

Price and performance patterns

Category-level pricing differences
<img width="1562" height="834" alt="image" src="https://github.com/user-attachments/assets/bd05c861-97e2-4c68-af68-aed135497c40" />

**Recommendations**

Based on the analysis, the following data-driven recommendations can be considered:

App developers should monitor both installation volume and user ratings rather than relying on a single performance metric.

Categories with strong installation activity can be examined further to understand successful app characteristics.

Developers should track review volume and rating trends as indicators of user engagement and satisfaction.

Pricing decisions for paid applications should be evaluated alongside category demand and user engagement.

App size should be considered during product design because large applications may affect accessibility for users with limited device storage or network bandwidth.

Regular updates and user feedback analysis can help identify opportunities for improving application quality and retention.

**Conclusion**

The Google Play Store Analysis project demonstrates how exploratory data analysis and dashboard visualization can be used to understand application-market trends.

The project examines app categories, ratings, reviews, installations, pricing, application types, and other attributes to identify meaningful patterns. The Tableau dashboards make these findings easier to explore and communicate.

Overall, the project provides a structured analytical view of the Google Play Store dataset and demonstrates practical skills in data cleaning, exploratory analysis, visualization, dashboard development, and business insight generation.

**Project Files**

googleplaystore.csv – Main Google Play Store application dataset.

googleplaystore_user_reviews.csv – User review dataset.

Google Play Store Analysis Tableau.twb – Tableau workbook.

EDA notebook – Data cleaning, exploration, visualizations, and key insights.

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
