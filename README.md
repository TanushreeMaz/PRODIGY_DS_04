<p align="center">
  <img src="images/Twitter.jpg" width="100%">
</p>




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


## Volume Leaderboards
* **Top Mentioned Topics:** Top 10 volume chart.
* **Top Mentioned Topics - Positive:** Highest positive engagement drivers.
* **Top Mentioned Topics - Negative:** Brand risk absolute spikes.


## Categorical Deep Dives
* **Sentiment by Topic:** 100% stacked column composition.
* **Least Discussed Topics:** Discrete color categorical treemap.


# Dashboard Preview

<img width="1904" height="944" alt="image" src="https://github.com/user-attachments/assets/b40806b2-32ac-4ddf-aff3-df86cb6fc1af" />


# Key Metrics

| Metric | Value |
| --- | --- |
| Total Tweets Analyzed | 74,823 |
| Total Negative Volume | 22,624 |
| Total Positive Volume | 20,932 |
| Overall Negativity Rate | 30.2% |
| Overall Positivity Rate | 27.9% |
| Unique Topics Monitored | 32 |
| Peak Topic Volume (*League of Legends*) | 2,414 |
| Maximum Brand Risk Volume (*Madden NFL*) | 1,712 |
| Maximum Positive Engagement Volume (*World of Warcraft*) | 744 |
| Neutral Conversation Share | 24.5% |


# # Project Structure

```text

Twitter-Sentiment-Analysis/
│
├── Data/
│   ├── twitter_training.csv
│   ├── twitter_validation.csv
│   └── twitter_cleaned.csv
│
├── Python Analysis/
│   ├── Twitter_Sentiment_EDA.ipynb
│   ├── Sentiment_Distribution_EDA.png
│   └── Sentiment_Distribution_Across_Top_Topics_EDA.png
|   └── Top_Topics.png
│
├── Dashboard Preview/
│   └── Dashboard_Overview.png
│
├── Reports/
│   └── Twitter_Sentiment_Analysis_Insights.pdf
│
├── images/
│   └── Twitter.jpg
│
├── README.md
│
└── requirements.txt
```


# Tools & Technologies

| Category | Tools |
| :--- | :--- |
| **Programming** | Python |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Business Intelligence** | Tableau |
| **Development** | Jupyter Notebook |


# Key Findings

| Analysis Area | Insight |
| :--- | :--- |
| **Global Sentiment Trend** | Negative conversation represented the single largest global share at 30.17%[cite: 1]. |
| **Baseline Platform Footprint** | Dynamic analysis covered a massive audience scale of 74,823 interactive dashboard elements. |
| **Max Volume Leader** | *League of Legends* spearheaded total platform engagement with 2,414 total tweets[cite: 1]. |
| **Highest Risk Entity** | *Madden NFL* drove severe platform friction, concentrating 1,712 purely negative tweets. |
| **Top Positive Anchor** | *World of Warcraft* emerged as the brand champion with a community-leading 744 positive tweets. |
| **Target Audience Scope** | Mentions spanned 32 distinct entities, tracking 3,757 negative vs. 3,472 positive unique users. |
| **Data Integrity Engine** | Preprocessing pipeline successfully caught and removed 686 empty string records[cite: 1]. |



# Conclusion

* **Sector Domination:** Gaming drives the highest overall public participation.
* **Data Hygiene Mandate:** Pre-cleaning empty text noise is mandatory for accurate metrics.
* **Strategic Synergy:** Python-to-Tableau pipelines convert chaotic streams into clear strategy.
* **Real-Time Risk:** High negative spikes flag immediate product issues requiring mitigation.
* **Asset Replication:** High-performing brand anchors provide frameworks for struggling assets.
* **Visual Clarity:** Unified, discrete color maps reduce insight delivery time down to 3 seconds.




# About

**Tanushree Mazumdar**
Data Analyst | Data Science Intern @ Prodigy InfoTech
Simplilearn & IBM Certified Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tanushree-mazumdar2195)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tanushreemaz)
[![Portfolio](https://img.shields.io/badge/Portfolio-0B3C5D?style=for-the-badge&logo=google-chrome&logoColor=white)](https://tanushreemaz.github.io)






















