# Communication of Sustainability of Universities via YouTube Channels

This repository contains the research project on **how universities utilize YouTube channels to communicate their environmental sustainability efforts**, and how these initiatives are received by the online community.

## Project Overview

Universities play a pivotal role in addressing global challenges related to environmental sustainability. This research explores how universities use YouTube to communicate sustainability initiatives and analyzes the engagement and reactions of the online community. The project examines data from the YouTube channels of several universities and performs a sentiment analysis to gauge public responses to these efforts.

### Research Questions:
1. **How do universities utilize their official social media channels (YouTube) to communicate environmental sustainability efforts to the public?**
2. **How does the online community respond to these initiatives by universities?**

## Project Structure

- **Data Collection**: Data was gathered from the official YouTube channels of selected universities, focusing on environmental sustainability videos between January 2020 and June 2024.
- **Analysis Methods**:
  - **Engagement Metrics**: Total likes, comments, views, and video counts were analyzed to assess audience engagement.
  - **Sentiment Analysis**: Comments were categorized into positive, neutral, and negative to understand the public's sentiment.
  
### Tools and Technologies Used:
- **Python**: For data analysis and content extraction using YouTube API.
- **Pandas**: For data manipulation and management.
- **Matplotlib & Seaborn**: For visualizing engagement metrics.
- **NumPy**: For numerical operations.
- **Google API Client**: For data collection from YouTube.

## Key Findings

1. **Engagement Trends**: Universities like Stanford and Melbourne consistently posted more content related to sustainability, leading to higher engagement in terms of views, likes, and comments.
2. **Audience Interaction**: While views were the most common form of engagement, comments were the least frequent, highlighting room for improving interactivity.
3. **Sentiment Analysis**: The audience had mixed reactions to the content, with universities like Stanford receiving both highly positive and critical feedback on their sustainability videos.

## Files in the Repository

- **/data/**: Contains the data collected from the YouTube channels.
- **/scripts/**: Python scripts used for data collection, processing, and analysis.
  - `youtube_data_collection.py`: Script for gathering data from YouTube using the Google API.
  - `sentiment_analysis.py`: Script for performing sentiment analysis on YouTube comments.
- **/visualizations/**: Graphs and plots generated from the analysis.
- **/report/**: The final research paper summarizing the findings.

## How to Run the Project

### Prerequisites:
- Python 3.x
- Install required libraries using the following command:
  ```bash
  pip install -r requirements.txt
  add google api yours key
