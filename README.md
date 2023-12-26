# Twitter Sentiment Analysis

## Overview
This repository contains the code and analysis for a Twitter Sentiment Analysis project. The data was sourced from Kaggle by making an API call. The analysis includes data preprocessing, cleaning, and exploratory data analysis (EDA) at an Uber level.

## Data Preprocessing
# Duplicate Removal: Identified and removed duplicate records in the "id" column, which had different values for polarity.
# Aggregation: Aggregated the dataset at the "id" level to get average values for polarity.
# Date Extraction: Extracted year, month, and weekday columns from the date field for further analysis.

## Data Analysis (EDA)
# Time Frame Analysis: Explored the dataset with a focus on time, analyzing trends month-wise and weekday-wise.
# Unique Tweets Analysis: Investigated unique tweets based on both months and weekdays.
# Wordcloud Summary: Conducted tweet text analysis using wordcloud to visualize word frequency across weekdays and weekends.
# Sentiment Analysis: Plotted wordcloud summaries against different polarities of sentiments.

## URL Analysis
# URL Extraction: Extracted URLs tagged in the tweet text column.
# Popular URLs: Investigated the most popular URLs based on the tweets they were tagged into.

## Text Similarity Analysis
Jaccard Distance: Conducted tweet text similarity analysis using Jaccard distance.

# Notebook Reference
For detailed information and step-by-step execution, please refer to the notebook in this repository.

# Note
The analysis presented here provides insights into the sentiment of tweets, their temporal patterns, and textual content. The data cleaning and preprocessing steps ensure the reliability of the analysis results. For detailed findings and visualizations, please refer to the notebook.

Feel free to explore the code and adapt it for your own projects or analyses. If you have any questions or suggestions, please create an issue or reach out.

Happy analyzing!
