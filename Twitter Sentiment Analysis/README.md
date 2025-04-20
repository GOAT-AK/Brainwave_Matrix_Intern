# Twitter Sentiment Analysis Project

A Data analysis project focused on understanding public sentiment on Twitter. This initiative leverages natural language processing (NLP) to analyze tweet content, identify sentiment trends, and generate actionable insights for social media monitoring and audience engagement strategies.

## Table of Contents
- [Brief](#brief)
- [Project_Goal](#project_goal)
- [DataSet](#dataset)
- [Tech_Stack](#tech_stack)
- [Tools](#tools)
- [Key_Achievements](#key_achievements)
- [Key_Findings](#key_findings)
- [Key_Recommendations](#key_recommendations)

## Brief

This project analyzes a Twitter dataset to uncover sentiment patterns across time. By categorizing tweets into positive and negative sentiments, the analysis reveals behavioral insights from users on social media. Key trends are visualized to support marketers, communication teams, and analysts in understanding public mood and engagement peaks.

## Project_Goal

- Clean and preprocess 1.6 million raw tweets
- Classify tweets into Positive and Negative sentiments using NLP
- Identify most active users by sentiment class
- Analyze trending hashtags per sentiment
- Explore tweet sentiment patterns over time and by hour of day
- Visualize findings for stakeholder presentation

## DataSet

- **Source**: [Sentiment140 Dataset – Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)
- **Size**:  1,600,000 tweets
- **Features**: Used: target (sentiment label), user, date, text
- **Sentiment Mapping**: 0 = Negative, 4 = Positive

## Tech_Stack

- **Python**: preprocessing, and analysis
- **Pandas, NumPy**: Data cleaning and manipulation
- **Matplotlib, Seaborn**: Data visualization
- **NLTK**: Natural language processing and sentiment mapping
- **WordCloud**: For visual representation of keyword frequencies


## Tools

- Jupyter Notebook
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- nltk
- re
- collections

## Key_Achievements

- Processed and cleaned over 1.6 million tweets including:
    - Removal of URLs, mentions, punctuation, and stopwords
    - Standardization to lowercase text
- Successfully mapped raw sentiment values into categorical sentiment classes
- Built custom functions to extract and visualize hashtags
- Generated time-based sentiment trends and word clouds per sentiment
- Identified top positive and negative users by tweet volume



## Key_Findings

- **Sentiment Over Time**: A significant spike in both sentiments was observed around late May to early June 2009, indicating a major external trigger or event.

- **Word Cloud Insights**:  
  - Positive tweets often included words like **“thank”**, **“fun”**, **“yay”**, **“awesome”**, and **“amazing”**.  
  - Negative tweets commonly featured terms such as **“hate”**, **“miss”**, **“sad”**, **“wish”**, and **“suck”**.

- **Top Users**:  
  - *Most Positive*: `what_bugs_u`, `DarkPiano`, `VioletsCRUK`  
  - *Most Negative*: `lost_dog`, `tweetpet`, `webwoke`

- **Hashtag Engagement**:  
  - *Positive Sentiment*: `#followfriday`, `#ff`, `#musicmonday`, `#seb`, `#marsiscoming`  
  - *Negative Sentiment*: `#fail`, `#iranelection`, `#squarespace`, `#iphone`, `#iremember`

- **Hourly Sentiment Trends**:  
  - Positive sentiment peaks between **22:00 to 23:00**, aligning with user relaxation and leisure time.  
  - Negative sentiment spikes between **06:00 to 10:00**, possibly reflecting stress or early-day frustrations.



## Key_Recommendations

- **Evening Posting Strategy**: Schedule positive or promotional content between **8 PM and 11 PM**, when users are most likely to engage with uplifting messages.

- **Monitor Morning Sentiment**: Negative sentiment tends to rise between **6 AM and 10 AM**. Social media and customer support teams should stay alert during these hours to quickly address issues and maintain brand reputation.

- **Hashtag Monitoring**: Hashtags like `#fb` and `#squarespace` appear across both sentiment classes. Brands should monitor these closely for context and respond accordingly to manage both praise and criticism effectively.

- **Event-Based Sentiment Tracking**: Sudden spikes in sentiment—positive or negative—may indicate viral events or crises. Integrating real-time sentiment tracking can support timely campaign launches or crisis response.

- **Content Tailoring**: Use sentiment-driven insights to adjust tone, messaging, and timing of content for maximum audience resonance and engagement.


