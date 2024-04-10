# **Squid Game Sentiments: Twitter's Take**

## **Introduction**
"Squid Game," created by Hwang Dong-hyuk for Netflix, is a South Korean TV series. It follows a secretive competition where 456 financially struggling players risk their lives in deadly children's games to win a ₩45.6 billion prize. The show's title is inspired by a traditional Korean children's game.

Released worldwide on September 17, 2021, "Squid Game" received praise and gained huge popularity. It became Netflix's most-watched series and topped the charts in 94 countries. Within the first four weeks, it was watched in over 142 million households, totaling 1.65 billion viewing hours.

## **About the Analysis**
This analysis aimed to explore how Twitter users perceive of the series. I sought to identify the top hashtags associated with the show, gauge anticipation for the next series, understand viewers' sentiments, determine the locations generating the most tweets, and assess the overall conversation surrounding the Netflix series on Twitter.

## **Use Case**
A comprehensive analysis such as this one can be invaluable for any company with a social media presence seeking to predict customer sentiment automatically. By automating the process, companies can efficiently gauge whether their customers are satisfied or dissatisfied without the need for manual review of thousands of tweets and customer reviews. This streamlined approach enables businesses to stay proactive in addressing customer concerns and enhancing overall satisfaction levels.

## **Process of Data Analysis**
To extract meaningful insights from available data, a series of procedures must be undertaken. It's vital to identify and follow these procedures diligently, as each stage plays a pivotal role in ensuring that the data is processed effectively to provide actionable information. Below are the key steps I followed in this process:

- Data Collection
- Data Evaluation and Cleaning
- Data Preparation
- Sentiment Analysis
- Data Visualization
- Communication of Findings and Insights
  
## **1. Data Collection**
The data collection process consisted of downloading the dataset from Kaggle, a platform that hosts datasets and data science resources. This dataset, related to the Netflix series "Squid Game," provided the necessary information for analysis, including tweets and other relevant data.

## **2. Data Evaluation and Cleaning**
The code verifies for duplicate users, ensures all values are present, replaces any missing locations with 'No Location', and eliminates unnecessary columns.

## **3. Data Preparation**
The code conducts preprocessing on tweets, readying them for sentiment analysis. This includes lowercase conversion, URL removal, character repetition elimination, stop words, punctuation, numbers, and emoji removal. The remaining words undergo lemmatization for subsequent analysis. Additionally, the code defines functions for extracting hashtags and identifying Squid Game seasons.

## **4. Sentiment Analysis**
The code employs the TextBlob library for sentiment analysis on preprocessed tweets. It computes the polarity score for each tweet, representing its sentiment. Based on the polarity score, sentiments are categorized as negative, neutral, or positive. These sentiment analysis results are then appended as columns to the dataframe.

## **5. Data Visualization**
I exported the finalized CSV file to PowerBI, where I created a dashboard to visually represent my analysis more effectively.

## **6. Conclusion**
This code framework is designed to analyze Twitter's perspective on the Squid Game TV series. It collects, cleans, preprocesses, and analyzes data to uncover insights into sentiment and popular topics discussed on Twitter regarding the show.





