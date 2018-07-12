# Sentiment_v_Stock
## Objective
The objective of this project was to understand what correlation exists between a company's stock price and the sentiment around the company based on global news headlines. I compared daily changes in close prices of the stock to aggregated daily sentiment.

## Model Improvement
While this correlation was interesting, I wanted to ensure quality in the articles that were being analyzed. For this, I trained a multinomial naive bayes model on a dataset of news articles that was pre-labeled for their economic relevance. I used this trained model as a filter for the news headlines from which I was capturing and aggregating sentiment.

This 'economic-relevance filtering' approach did reduce noise in the data, but did not have a meaningful impact on the overall correlation between the sentiment and stock price.

## Next Steps
Future work will include increasing the dataset considered for the analysis. First, I will need to expand the timeline over which the sentiment is being analyzed from one-week (late August, 2017) to three to six months. The second step would be to increase the frequency of the comparison. Rather than aggregating on a daily basis, there is value on minimizing the time interval to a minute-by-minute analysis. 
