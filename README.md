# Project-2

Premise:  Back in the days, people used to exchage goods, or even trade gold for those goods. Nowadays, countries use different currencies that serve as fiat money in exchage for goods and services.Gary Gensler believes that Crypto is the next step in the evolution of money and trade barters. El Salvador has officially declared Bitcoin legal tender, while Turkey and China have banned it. Using the NewsAPi, we pulled 20 news articles relevant to Bitcoin in countries such as El Salvador, Guatemala, Panama, Brazil, Turkey, Iran, and China. We then calculated the overall sentiment of those news article and created a dataframe. One of the reasons El Salvador decided to adopt Bitcoin is to simplify the process for the diaspora to transfer money into El Salvador. Considering that factor, we collected some economic as well as demographic data from the IMF and used machine learning to find hidden correlation between the economics. Using the sentiment analysis and the machine learning, we are considering which of the seven countries should or could be next in adopting Bitcoin as legal tender. He believes that it is the next step in the evolution of money and trade barters. Back in the days, people used to trade goods for goods, or for gold, and then fiat money, the next step would be crypto.


## Dataframe Containing Sentiment

Using NewsApi, we pulled 20 relevant news articles on Bitcoin regarding these seven countries. The dataframe contains a sentiment score on the title of the article,
the description of the article, as well as the content of the article. After collecting the score of each aspect from the articles, an "Overall" score is calculated by applying a weight of 0.6, 0.3, 0.1, to the content, description, and title respectively.
![image](https://user-images.githubusercontent.com/79224741/122848608-e7947580-d2d7-11eb-9dd4-0620af42aac6.png)

## Overall Sentiment
After calculating the overall sentiment from 140 articles from 7 countries, the average of overall sentiment score of articles from each country is calculated and then graphed on a bar chart.

![image](https://user-images.githubusercontent.com/79224741/122849132-edd72180-d2d8-11eb-97ac-0509a78b8d82.png)

