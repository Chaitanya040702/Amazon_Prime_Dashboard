# Amazon Prime Analysis 

## Table of Content

- Project Overview
- Project Goal
- Data Source
- Tools Used
- Data Cleaning and Preparation
- Data Analysis
- Findings / Results
- Recommendations
- Limitations
- References

## Project Overview

This project explores and analyzes the content catalog available on Amazon Prime Video. The goal is to understand the platform’s offerings in terms of content type, release trends, genre distribution, and country-wise availability. Insights derived can assist content strategists, marketers, or media analysts in making data-informed decisions

## Project Goal

- The primary objective of the dashboard is to visually represent key trends and patterns in Amazon Prime’s content library. It aims to:

1. Help stakeholders identify popular content categories and producing countries
2. Highlight gaps in metadata like ratings and cast information
3. Enable quick filtering by year, type, genre, and country for content strategy decisions
4. Provide drill-down capabilities for detailed analysis using Power BI interactive features

## Data Source

- Dataset: amazon_prime_titles.csv (sourced from Kaggle)

- Contains metadata about Amazon Prime content including title, type, release year, genres, country, cast, director, date added, and rating.

- Manually reviewed and cleaned for consistency and completeness.

## Tools Used

- Power BI (for dashboard creation and data visualization)

- Microsoft Excel (for initial data review)
  
## Data Cleaning and Preparation

- Handled missing values in fields like director, cast, rating, and country

- Converted date_added to a proper datetime format

- Split multivalued columns (e.g., listed_in, cast, country) for granular analysis

- Filtered out irrelevant or duplicate entries
 
## Data Analysis

- Trend analysis by year of release and date added

- Distribution of content by type (Movies vs. TV Shows)

- Top genres and categories offered on Amazon Prime

- Leading countries contributing to Amazon Prime’s content library

- Ratings distribution to assess content maturity level

## Findings / Results

- Movies dominate the platform, making up the majority of content

- The peak year for content addition was [e.g., 2020]*

- U.S. and India are the top content-producing countries

- Drama, Comedy, and Action are the most common genres

- A significant portion of content is unrated or has unknown ratings

## Recommendations

- Increase regional content acquisition to diversify offerings

- Improve metadata consistency (especially ratings and country fields)

- Balance the content mix with more TV shows in emerging genres

- Use ratings data to tailor parental control features and recommendations

## Limitations

- Dataset lacks user engagement or viewership metrics

- No data on subtitle languages or dubbing availability

- Incomplete information in some key columns like cast and rating

- No regional segmentation beyond country (e.g., state, city)

## References

- Dataset: Amazon Prime Titles Dataset – Kaggle

- Power BI Template: Custom-built dashboard available in repo

- External tools: Power BI documentation and cleaning best practices




