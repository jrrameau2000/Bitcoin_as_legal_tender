# Project-2

Hypothesis: Use NLP to analyze general sentiment of leadership, prominent characters, and people about Bitcoin/crypto in a certain countries. El Salvador has officially declared Bitcoin legal tender, while Turkey and China have banned it. Major U.S. corporations have recently been using crypto as a form of ransomware, and their are a lot of negative sentiments associated towards it. We can use a Time-series analysis to track the value, inflation of certain currencies and possibly recommend which currencies should adopt crypto as currency and possible risk. Gary Gensler, chairman of the SEC, who used to teach blockchain at MIT has been normalizing talks around Bitcoin and its transition to becoming legal tender. He believes that it is the next step in the evolution of money and trade barters. Back in the days, people used to trade goods for goods, or for gold, and then fiat money, the next step would be crypto.


## Dataframe Containing Sentiment

Using NewsApi, we pulled 20 relevant news articles on Bitcoin regarding these seven countries. The dataframe contains a sentiment score on the title of the article,
the description of the article, as well as the content of the article. After collecting the score of each aspect from the articles, an "Overall" score is calculated by applying a weight of 0.6, 0.3, 0.1, to the content, description, and title respectively.
![image](https://user-images.githubusercontent.com/79224741/122848608-e7947580-d2d7-11eb-9dd4-0620af42aac6.png)

## Overall Sentiment
After calculating the overall sentiment from 140 articles from 7 countries, the average of overall sentiment score of articles from each country is calculated and then graphed on a bar chart.

![image](https://user-images.githubusercontent.com/79224741/122849132-edd72180-d2d8-11eb-97ac-0509a78b8d82.png)

