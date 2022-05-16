# Sentiment-Analysis-about-Vaccine-Tweets
In this project, we explored the sentiments of the tweets and the relationships between sentiments and vaccination rates.

## Procedures
- Data Preprocessing
- Sentiment Analysis 
  - Simple Sentiment Analysis
  - NRC Sentiment Analysis
  - Vader Sentiment Analysis
- Exploratory Data Analysis
  - Word Clouds
  - Heat Map
- Machine Learning Modeling
  - Linear Regression
  - Random Forest
  - k-Nearest Neighbors
  - Multi-Layer Perceptron Regressor

## Conclusion
![Machine Learning Model Result](https://github.com/XueyingHu/Sentiment-Analysis-about-Vaccine-Tweets/blob/main/Dataset/Result.png)
Though from simple sentiment analysis and NRC analysis, we have seen that positive emotions are significant and have positive correlations with vaccination rates, the model that has the lowest root mean squared error (the models constructed with Vader Sentiment scores) doesn’t align with this result. 

Thus, we can’t conclude that sentiments would impact vaccination rates, we believe that further text data on policies within a certain period/country is needed to prove the relationship. Furthermore, we could also include topic analyses (LDA) to perhaps further identify certain topics that may have appeared at different time points in different countries to identify how different topics related to vaccination rates.

Details can be found in the report and the presentation slide.

## Language & Tools
- Python 3.6+
- Power Bi
- Google Map API

## Dependencies
- numpy
- pandas
- nltk
- vaderSentiment
- statsmodel
- sklearn
