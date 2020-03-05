# Sentiment-Analysis
Here I will show you how to make a sentiment analysis by using Tweeter data. For this project, I have compiled two versions:

1.Snapshot Sentiment Analysis which will take a screenshot of the data at the moment you execute the script and analyze it. The size of data varies depending on the number of people talking at that moment for your keyword.

2.Continues Sentiment Analysis which will data the data from Tweeter, analyze it (in the real time) and place it to a CSV file('List.csv')
For this version, I am using StreamListener. For more information please go here: http://docs.tweepy.org/en/latest/streaming_how_to.html

To visualize the result, I have created a separated file which will use the CSV file('List.csv') as data source. Here I am using Animation from Matplotlib which will auto populate the chart with data.
