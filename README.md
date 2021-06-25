# A Case for Crypto as Legal Tender
![crypto_pic](https://user-images.githubusercontent.com/78506291/123009759-58e13080-d38b-11eb-8763-e1a69c502e73.PNG)

Back in the days, people used to exchage goods, or even trade gold for those goods. Nowadays, countries use different currencies that serve as fiat money in exchage for goods and services.Gary Gensler believes that Crypto is the next step in the evolution of money and trade barters. El Salvador has officially declared Bitcoin legal tender, while Turkey and China have banned it. Using the NewsAPi, we pulled 20 news articles relevant to Bitcoin in countries such as El Salvador, Guatemala, Panama, Brazil, Turkey, Iran, and China. We then calculated the overall sentiment of those news article and created a dataframe. One of the reasons El Salvador decided to adopt Bitcoin is to simplify the process for the diaspora to transfer money into El Salvador. Considering that factor, we collected some economic as well as demographic data from the IMF and used machine learning to find hidden correlation between the economics. Using the sentiment analysis and the machine learning, we are considering which of the seven countries should or could be next in adopting Bitcoin as legal tender. He believes that it is the next step in the evolution of money and trade barters. Back in the days, people used to trade goods for goods, or for gold, and then fiat money, the next step would be crypto.

## Intro
On June 5th President Nayib Bukele announced El Salvador's intention to accept Bitcoin as legal tender and to one day mine Bitcoin in El Salvador. This announcement was a shock around the world as El Salvador became the first nation to officially use Bitcoin as legal tender. This announcement raised many questions. What factors lead to this decision? What affects would this have on El Salvador? or Bitcoin in the midst of trending negative sentiment?  What countries if any will follow suit? 

## Hypothesis
We believe that countries, have an overall positive sentitment about cryptocurrency, that have younger leadership, high migration to the US, high inflation and renewable energy capacity. 

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

## The Migration Factor
"In the short term this will generate jobs and help provide financial inclusion to thousands outside the formal economy," Bukele said in a video shown at the Bitcoin 2021 conference in Miami. Across the world one of the major benefits of using cryptocurrency was the ability to send money globally. El Salvador specifically has an enormous case to make when it comes to the rate in which it's citizen are moving to the US. 

## Yearly Legal Migration to U.S
![bokeh_plot](https://user-images.githubusercontent.com/78506291/123001051-50362d80-d37e-11eb-9c28-8315db4f0339.png)

## Percentage of Mirgants to U.S by Naturalized Country Population
![imm_pct_bar](https://user-images.githubusercontent.com/78506291/123002012-6395c880-d37f-11eb-9a95-fddd3603761b.PNG)

## Renewable Energy Factor
One of the other major contributing factors to El Salvador's using Bitcoin as legal tender is their ability to mine Bitcoin in facilities powered by renewable energy. 

## Remewable Energy Capacity by Region
![renewable_energy](https://user-images.githubusercontent.com/78506291/123003222-e4a18f80-d380-11eb-99d2-9ff65e985e56.PNG)

## Linear Regression Model!
[Linear_reg](https://user-images.githubusercontent.com/78506291/123010031-d0af5b00-d38b-11eb-807d-ed9920caa63e.PNG)
![image](https://user-images.githubusercontent.com/78506291/123010145-018f9000-d38c-11eb-929c-1504f0fe0a5a.png)


