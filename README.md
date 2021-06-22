# Project-2

Premise:  Back in the days, people used to exchage goods, or even trade gold for those goods. Nowadays, countries use different currencies that serve as fiat money in exchage for goods and services.Gary Gensler believes that Crypto is the next step in the evolution of money and trade barters. El Salvador has officially declared Bitcoin legal tender, while Turkey and China have banned it. Using the NewsAPi, we pulled 20 news articles relevant to Bitcoin in countries such as El Salvador, Guatemala, Panama, Brazil, Turkey, Iran, and China. We then calculated the overall sentiment of those news article and created a dataframe. One of the reasons El Salvador decided to adopt Bitcoin is to simplify the process for the diaspora to transfer money into El Salvador. Considering that factor, we collected some economic as well as demographic data from the IMF and used machine learning to find hidden correlation between the economics. Using the sentiment analysis and the machine learning, we are considering which of the seven countries should or could be next in adopting Bitcoin as legal tender. He believes that it is the next step in the evolution of money and trade barters. Back in the days, people used to trade goods for goods, or for gold, and then fiat money, the next step would be crypto.


## Dataframe Containing Sentiment

Using NewsApi, we pulled 20 relevant news articles on Bitcoin regarding these seven countries. The dataframe contains a sentiment score on the title of the article,
the description of the article, as well as the content of the article. After collecting the score of each aspect from the articles, an "Overall" score is calculated by applying a weight of 0.6, 0.3, 0.1, to the content, description, and title respectively.
![image](https://user-images.githubusercontent.com/79224741/122848608-e7947580-d2d7-11eb-9dd4-0620af42aac6.png)

## Overall Sentiment
After calculating the overall sentiment from 140 articles from 7 countries, the average of overall sentiment score of articles from each country is calculated and then graphed on a bar chart.

![image](https://user-images.githubusercontent.com/79224741/122849132-edd72180-d2d8-11eb-97ac-0509a78b8d82.png)

## What's Age Got to do with it?
Mid June of this year El Salvador relesased huge news about changing its legal tender to Bitcoin. This groundbreaking information made El Salvador the first country to make such a bold update to its financial system. Behind every bold decision, is a bold individual. It just so happens that El Salvador is under the leadership of 39 year old Nayib Bukele. Bitcoin has a history of beening favored by the young and bashed by the old. Younger crowds are challenging the status quo when it comes to politics, sexuality, womens rights and even finance. Shifting the power of the Federal Reseve to Blockchain is an active goal that "whippersnappers" are looking to accoomplish. The data below shows some interesting Bitcoin and age data.

![image](https://user-images.githubusercontent.com/79435102/122999026-bf5e5280-d37b-11eb-98f0-8f3a4f26d4a1.png)

![image](https://user-images.githubusercontent.com/79435102/122999212-fa608600-d37b-11eb-9b90-4756633dd940.png)

![image](https://user-images.githubusercontent.com/79435102/122999299-15cb9100-d37c-11eb-813c-49e4c6ee0be3.png)

![image](https://user-images.githubusercontent.com/79435102/122999367-31369c00-d37c-11eb-98a8-057fd03358ed.png)
