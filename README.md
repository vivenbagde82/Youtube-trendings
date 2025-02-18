# YouTube Trending Data Analysis

This project focuses on collecting, cleaning, and analyzing YouTube trending data using the Google API Key. Various statistical and visual analyses were performed to understand the trends and relationships within the data.

## Table of Contents
- [Introduction](#introduction)
- [Data Collection](#data-collection)
- [Data Cleaning](#data-cleaning)
- [Data Analysis](#data-analysis)
- [Visualizations](#visualizations)
- [Inferences](#inferences)
- [Conclusion](#conclusion)
- [How to Run the Project](#how-to-run-the-project)
- [References](#references)

## Introduction
The aim of this project is to analyze YouTube trending data to uncover patterns and insights. The project involves data collection, cleaning, visualization, and statistical analysis to understand the distribution of views, likes, comments, and the relationship between video attributes and engagement metrics.

## Data Collection
Data was collected using the Google YouTube Data API. The API provided information on trending videos, including their views, likes, comments, and other attributes.

### Setting Up the Google API
To collect data from YouTube, you need to set up an API. Follow these steps:

1. Go to [Google Cloud Console](https://console.cloud.google.com/).
2. Click on the project drop-down at the top, then “New Project”.
3. Enter a project name and click “Create”.
4. In the Google Cloud Console, navigate to “APIs & Services” > “Library”.
5. Search for “YouTube Data API v3” and click on it.
6. Click “Enable”.
7. Go to “APIs & Services” > “Credentials”.
8. Click “+ CREATE CREDENTIALS” and select “API key”.
9. Copy the generated API key.

## Data Cleaning
The collected data was cleaned by handling missing values and fixing datatypes to ensure consistency and accuracy for analysis.

## Data Analysis
The analysis involved:
- Drawing graphs for views, likes, and comments distribution
- Finding correlations between views, likes, and comments
- Mapping data to their respective categories
- Analyzing which category of videos trends the most in India
- Calculating the length of each video and analyzing the relationship between video length and engagement metrics

## Visualizations
- **Distribution Graphs:** Visualizations of views, likes, and comments distribution
- **Correlation Analysis:** Graphs showing the correlation between views, likes, and comments
- **Category Trends:** Graphs depicting which categories trend the most in India
- **Engagement Analysis:** Graphs for views, likes, and comments for each category
- **Video Length Analysis:** Graphs showing the relationship between video length and engagement metrics

## Inferences
By analyzing the visualizations, we made several inferences:
- The relationship between views, likes, and comments
- Categories that are most likely to trend in India
- The impact of video length on views, likes, and comments

## Conclusion
This project provides insights into YouTube trending data and helps understand the factors that contribute to video engagement. The analysis can be used to guide content creation strategies for maximizing reach and engagement on YouTube.
