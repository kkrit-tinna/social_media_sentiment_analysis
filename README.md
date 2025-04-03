# Social_Media_Sentiment_Analysis

## About Dataset
This dataset is a Kaggle Dataset named **'Social Media Sentiments Analysis Dataset'**
<br>
It captures a vibrant tapestry of emotions, trends, and interactions across various social media platforms.
<br><br>
This dataset provides a snapshot of user-generated content, encompassing text, timestamps, hashtags, countries, likes, and retweets. 
Each entry unveils unique stories—moments of surprise, excitement, admiration, thrill, contentment, and more—shared by individuals worldwide.

## Description
* This project aims to understand sentiment changes from 2010 to 2023 on popular social media platforms based on certain attributes and how they impact each other.
* This project explores the standard procedure of data analysis, including data preprocessing, feature engineering, EDA and supervised machine learning.
* This project introduces the standard procedure of natural language processing(text clearning, word embedding, etc.), and used multiclass classification models for sentiment analysis.
* This proect optimizes text classification using  pre-trained LLM model BERT, and preprocess datasets from dataframe to datasets in tensors using pytorch.
* This project leverages some popular data-analyic tools, including pandas, matplotlib, seaborn, sckiitlearn and a decent usage of natural language processing tool-nltk.

## Getting Started

### Dependencies
* The process of Analysis is stored in the Jupyter Notebook **'sentiment_analysis.ipynb'**.
* Pre-req Python Libraries include: re, pandas, maplotlib, seaborn, scikitlearn, wordcloud, nltk, torch, transformers, tqdm.

### Installing
* You can download this project [here](https://github.com/kkrit-tinna/social_media_sentiment_analysis.git) or on [kaggle](https://www.kaggle.com/code/shikristin/sentiment-analysis-nlp-linearsvm-bert).

### Executing Program
* To begin, locate jupyter notebook **'sentiment-analysis-nlp-linearsvm-bert.ipynb'** and run all cells for results.
* Major plots are saved to the current repository for reference.

### Potential Issues
* Dataset is generated using chatGPT, which can be problematic in the accuracy and reliability of this dataset.
* Based on the sentiment analysis of each post' original text, there are issues of mislabeling sentiments, which can significantly affect the sentiment analysis.
* Based on the sentiment analyzer, some positive and negaive words are mis-categorized as neutral, which can lead to overestimation of 'neutral' in any sentiment results.
* Based on BERT's training accuracy and test accuracy after 20 epoches, the issue of overfitting still persists.
  
## Resources
Learnng description of this dataset @https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset/data
Leanining sentiment anayler @https://github.com/cjhutto/vaderSentiment

## Author
Yifei Shi


## Version History
* 0.1
    * Initial Release
 
* 0.2
    * Upgrade natural language process with text preprocessing, word embedding, and sentiment analysis using multi-class classification modeling
    * Add visualization plots to illustrate sentiment distribution across week, month, year, platform, and country.
 
* 0.3
    * Add wordclouds to identify popular keywords associated with postive/negative/neutral sentiments, and upgrade visualization in time distribution & country distribution
    * Optimize natural language processing with pre-trained LLM and improved the accuracy of text-sentiment alignment to 0.7.
