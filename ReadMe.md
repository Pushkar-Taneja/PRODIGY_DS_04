# Sentiment Analysis on Social Media Data

## Overview

This project analyzes and visualizes sentiment patterns in social media data (primarily tweets) to understand public opinion and attitudes towards specific topics or brands. The dataset includes tweets labeled with sentiments such as Positive, Negative, Neutral, and Irrelevant. The analysis and visualizations were performed using Python and various data science libraries such as Pandas, Seaborn, and Matplotlib.


## Dataset

### `twitter_training.csv`
This file contains the training data, including tweets labeled with sentiments. The dataset includes the following columns:
- `Text`: The tweet text.
- `Sentiment`: The sentiment of the tweet (Positive, Negative, Neutral, Irrelevant).
- `Platform`: The platform from which the tweet was posted (e.g., Twitter).

### `twitter_validation.csv`
This file contains the validation data, which follows the same format as the training dataset.

## Objective

The goal of this analysis is to:
1. Clean and preprocess the text data.
2. Analyze sentiment distributions.
3. Visualize sentiment trends using various plots.

## Steps

### 1. Data Cleaning
- Remove missing or irrelevant data.
- Preprocess text (e.g., remove stop words, special characters, and tokenize).

### 2. Sentiment Analysis
- Categorize tweets into sentiment categories (Positive, Negative, Neutral, Irrelevant).
- Calculate the average word count for each sentiment.

### 3. Visualizations
The following visualizations were created:

- **Sentiment Distribution across Platforms**: A countplot showing sentiment distribution across different platforms.
- **Barplot for Sentiment Distribution**: A bar chart showing the distribution of sentiments in the dataset.
- **Average Word Count by Sentiment**: Box plots showing the average word count for each sentiment category.
- **Correlation between Sentiment and Text Length**: Boxplots revealing how text length correlates with sentiment.

### 4. Insights
- Sentiments are fairly evenly distributed across platforms, but some platforms may have stronger associations with specific sentiments.
- Positive sentiments tend to have a higher average word count compared to Negative or Neutral sentiments.
- The relationship between sentiment and text length reveals that certain sentiments, like Negative or Irrelevant, tend to have shorter tweet lengths.

### 5. What I Learned
- Sentiment analysis provides valuable insights into the emotions and opinions shared on social media platforms.
- Cleaning and preprocessing textual data is a critical step in any NLP task, especially when dealing with noisy or unstructured text.
- Visualizations can help to quickly uncover patterns and trends, such as sentiment distribution and its relationship with tweet length.

## Conclusion

This analysis demonstrates how sentiment analysis can be applied to social media data to extract meaningful insights. The visualizations provided a clear view of sentiment distribution across different platforms and sentiment correlations with text length. These findings can be useful for understanding public opinion on various topics, brands, or events.



