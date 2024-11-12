# Yelp Restaurant Success Analysis

## Project Overview

This project analyzes factors influencing restaurant success in various metropolitan areas in the USA and Canada using the Yelp dataset. Through insights into user engagement, review patterns, and ratings, the project identifies factors that may contribute to the visibility and success of restaurants.

## Problem Statement

In a competitive restaurant industry, understanding the drivers of business success is crucial. This project investigates the relationships between user engagement metrics (reviews, tips, and check-ins) and restaurant success indicators (ratings, review counts).

## Objectives
1. Analyze the correlation between user engagement and restaurant ratings.
2. Identify engagement patterns that influence business success.
3. Provide actionable recommendations for enhancing restaurant performance based on user behavior and feedback.

## Hypothesis

- Higher levels of user engagement correlate with higher review counts and ratings.
- Positive sentiment in reviews is likely to contribute to better ratings and increased engagement.
- Sustained user engagement can indicate long-term business success.

## Data

The dataset used is a subset of Yelp's data containing information on businesses in the USA and Canada, with a focus on approximately 35,000 open restaurants. The JSON files contain data on businesses, reviews, users, tips, and check-ins.

## Methodology

1. **Data Loading and Cleaning**: JSON files were loaded into a database for easy access. The data was cleaned to focus on restaurant-specific metrics.
2. **Data Analysis**: 
    - Examined distribution patterns in review counts and ratings.
    - Analyzed engagement trends over time and the correlation with restaurant ratings.
3. **Visualization**: Key trends were visualized to showcase patterns in user behavior and restaurant success.

## Key Findings

- Restaurants with higher ratings generally show increased engagement in reviews, tips, and check-ins.
- Engagement levels peak at 4-star ratings, with a slight drop at the highest (5-star) level, indicating a saturation or selectivity point.
- Elite Yelp users contribute significantly to engagement; their reviews and check-ins provide critical visibility.
- Busiest hours for user engagement span 4 pm to 1 am, suggesting optimal times for operational focus.

## Recommendations

1. **Boost User Engagement**: Increasing review, tip, and check-in rates can enhance visibility and drive customer interaction.
2. **Engage Elite Users**: Partnering with Yelp Elite members can strengthen brand loyalty and amplify positive feedback.
3. **Optimize Operating Hours**: Staffing and resources can be adjusted to peak hours to capitalize on demand.
4. **Leverage Sentiment Analysis**: Regular feedback evaluation helps maintain service standards and improves customer satisfaction.

## Project Structure

- `Analysis.ipynb`: Analysis and visualization notebook.
- `Json_to_db.ipynb`: Notebook for JSON data import into the database.
- `PPT.pptx`: Presentation summarizing the findings and recommendations.

## Conclusion

This analysis provides insights for restaurant owners and marketers to leverage user engagement metrics effectively, helping to enhance business performance in a competitive market.

## Acknowledgments

Data provided by [Yelp Dataset](https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset).


