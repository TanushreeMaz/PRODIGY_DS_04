
# 📊 Twitter Sentiment Analysis

An exploratory data analysis project focused on analyzing sentiment patterns in Twitter data to understand public opinion and attitudes toward specific brands and topics. The analysis combines Python-based data exploration and Tableau dashboarding to uncover trends in Positive, Negative, Neutral, and Irrelevant sentiments across social media conversations.

The project focuses on transforming raw Twitter data into meaningful insights through data cleaning, preprocessing, sentiment analysis, topic-wise exploration, and interactive visual storytelling.

# 📌 Project Overview

This project analyzes Twitter entity-based sentiment data to extract insights about public perception of brands and topics.

The analysis focuses on answering key questions:
• What is the overall sentiment distribution in Twitter conversations?
• Which brands and topics are most frequently discussed?
• How does sentiment vary across different entities?
• Which topics show higher negative or positive sentiment trends?
• What patterns emerge in public opinion across social media discussions?


# Problem Statement

Social media platforms like Twitter generate large volumes of unstructured and noisy text data that reflect public opinions, emotions, and attitudes toward various brands and topics, making it difficult to interpret directly. This project aims to analyze and visualize sentiment patterns in Twitter data to understand how users perceive different entities by transforming raw tweets into structured insights. The goal is to identify sentiment trends, uncover public concerns, and analyze engagement patterns to better understand audience behavior and support data-driven decision-making for brand monitoring. 


# Project Objectives

• Analyze and understand the structure of Twitter sentiment dataset
• Clean and preprocess raw tweet data for accurate analysis
• Perform exploratory data analysis (EDA) to identify sentiment patterns
• Study the distribution of Positive, Negative, Neutral, and Irrelevant sentiments
• Identify most frequently discussed brands and topics
• Compare sentiment trends across different entities
• Extract insights on public perception and engagement behavior
• Create visualizations to effectively communicate findings
• Prepare cleaned dataset for Tableau dashboard development
• Build an interactive dashboard for data-driven storytelling


# Dataset Information

| Attribute       | Description                                         |
| --------------- | --------------------------------------------------- |
| Dataset Name    | Twitter Entity Sentiment Analysis Dataset           |
| Source          | Kaggle                                              |
| Type            | Text / Social Media Data                            |
| Format          | CSV                                                 |
| Records         | ~75,000+ tweets (combined train + validation)       |
| Columns         | ID, Topic, Sentiment, Tweet                         |
| Target Variable | Sentiment (Positive, Negative, Neutral, Irrelevant) |
| Features        | Tweet text, brand/topic entity, sentiment label     |
| Usage           | Sentiment analysis, EDA, visualization              |



#  Python Analysis

The dataset was processed and analyzed using Python through data cleaning, missing value handling, merging datasets, and exploratory data analysis. Sentiment labels were studied across different brands and topics to understand engagement patterns and public opinion trends.


## Data Preparation

• Loaded training and validation Twitter datasets
• Merged datasets into a single analysis frame
• Standardized column names and removed redundant rows
• Checked dataset structure and data types


## Data Cleaning

• Handled missing values in tweet text
• Removed null and incomplete records
• Ensured consistency in sentiment and topic labels
• Prepared clean dataset for analysis and visualization


## Exploratory Data Analysis

• Analyzed sentiment distribution (Positive, Negative, Neutral, Irrelevant)

<img width="704" height="427" alt="image" src="https://github.com/user-attachments/assets/643ddcea-2580-472f-a72c-c3dae6fc1c7d" />

Insight: Sentiment distribution shows mixed opinions with a slight dominance of negative sentiment overall.


• Identified most frequently discussed brands and topics

<img width="1280" height="814" alt="image" src="https://github.com/user-attachments/assets/96f1a548-8700-45c9-b35e-d97dfd6e28d0" />

Insights: Topic/brand analysis highlights gaming and tech as the most frequently discussed entities.

• Examined tweet volume distribution across entities

<img width="1337" height="680" alt="image" src="https://github.com/user-attachments/assets/3f2d1fa1-f96f-4445-9b47-07c93fbe9512" />

Insights: Tweet volume distribution indicates uneven engagement, with few brands driving most conversations.


## Feature / Insight Engineering

• Performed topic-wise sentiment aggregation using cross-tab analysis
• Compared sentiment patterns across top brands and topics
• Identified engagement differences across entities


## Visualization (Python)

• Sentiment distribution using count plots
• Top topics/brands using bar charts
• Topic-wise sentiment comparison using stacked bar plots
• Annotated visualizations for better interpretability


## Dataset Export

Cleaned dataset was exported and used for Tableau dashboard development to create interactive visual storytelling of sentiment insights.


# Tableau Dashboard

Python-based insights were transformed into an interactive Tableau dashboard to visualize:

• Sentiment distribution across Twitter conversations
• Brand-wise and topic-wise sentiment comparison
• Engagement patterns across different entities
• Public perception trends over social media discussions


# Dashboard Architecture-- Tableau Dashboard

## Summary & Distributions

* **Executive Performance Blocks:** Positive & negative KPI cards.
* **Sentiment Distribution (Donut Chart):** Macro volume percentage breakdown.
* **Overall Sentiment Distribution:** Baseline horizontal comparison strip.




