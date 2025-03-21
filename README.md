# SetimentAnalysis-TopicModelling
Project Title: Topic Modeling and Sentiment Analysis of British Airlines Reviews from Skytrax

Project Description:
This project involves the creation of a custom dataset by scraping reviews of British airlines from the Skytrax website, followed by data cleaning, topic modeling, and sentiment analysis to extract valuable insights from the text data. The goal is to understand the overall customer sentiment towards British airlines and uncover the main themes or topics present in customer feedback.

Objective:
The primary objective of this project is to:

Scrape data from the Skytrax website, focusing on reviews of British airlines.
Clean and preprocess the scraped text data to prepare it for analysis.
Apply topic modeling to identify the main themes or topics in the reviews.
Perform sentiment analysis to evaluate the overall sentiment (positive, negative, or neutral) of the reviews.
Visualize the results to gain actionable insights from the customer feedback.

Methodology:

Web Scraping:
Scrape reviews from the Skytrax website for British airlines using web scraping techniques (e.g., BeautifulSoup, requests, or Selenium).
Collect necessary data points such as the review text, ratings, and other relevant metadata.

Data Cleaning:
Clean the dataset by removing irrelevant or missing data.
Preprocess the reviews by tokenizing, removing stopwords, and lemmatizing the text for efficient analysis.

Topic Modeling:
Apply Latent Dirichlet Allocation (LDA) to the cleaned reviews to identify the main topics or themes discussed in the customer feedback.
Use the results of the topic modeling to gain insights into what customers are frequently talking about (e.g., service quality, food, comfort, etc.).

Sentiment Analysis:
Use VADER (Valence Aware Dictionary and sEntiment Reasoner) for sentiment analysis to classify the reviews into positive, negative, or neutral sentiment.
Analyze the sentiment of the reviews to understand customers' overall emotional tone towards the airlines.

Visualization:
Create visualizations such as histograms and bar charts to display the distribution of topics and sentiments across the dataset.
Visualize the sentiment distribution and the prevalent topics in the customer reviews to facilitate easy interpretation.

Results:
The project provides a comprehensive analysis of customer reviews for British airlines, offering insights into both the sentiment of customers and the topics most discussed in the feedback.
The LDA model helps to uncover the dominant themes in the reviews, while VADER sentiment analysis allows for an understanding of the emotional tone of the customers' experiences.
Visualizations of sentiment distribution and topic prevalence offer easy-to-understand insights that can help airlines improve their services.

Tools and Libraries Used:
Python: The core programming language for web scraping, text processing, and analysis.
BeautifulSoup and Requests: Used for web scraping to collect data from the Skytrax website.
NLTK: Natural Language Toolkit used for text preprocessing and sentiment analysis.
VADER: Used for performing sentiment analysis on the reviews.
Gensim: A library used to perform topic modeling using Latent Dirichlet Allocation (LDA).
Matplotlib and WordCloud: Used for visualizing the sentiment distribution and the topics.
Pandas: For handling and processing the dataset.

Conclusion:
This project provides an in-depth analysis of customer reviews for British airlines, uncovering important insights about customer satisfaction and key areas for improvement. By leveraging topic modeling and sentiment analysis, we can better understand the public's perception of the airlines, which can inform decision-making for improving customer service, addressing pain points, and enhancing overall customer experience.
