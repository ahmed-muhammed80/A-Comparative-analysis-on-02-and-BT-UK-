# (A Comparative Analysis of User Experience for O2 and BT Telecommunications using Sentiment Analysis on Social Media Data)

## by (Ahmed Muhammed)


## Dataset

> The purpose of this research is to conduct a sentimental analysis of O2 and BT, two major telecommunications companies in the UK. The study aims to explore the opinions and emotions expressed in online content related to these companies and classify them as positive, negative, or neutral.The study will use machine learning-based sentiment analysis techniques to analyze the text data collected from various online sources. The sentiment analysis tools will be selected based on their accuracy and suitability for the research objectives.

> The data used for this analysis was scraped from twitter, 
I started by downloading the Trenderfly script from the GitHub repository. After installing the required dependencies, I ran the script and was prompted to input my search queries, year to search from, and the number of tweets to scrape. I entered “O2, BT Telecommunications” as my search queries, “2013” as the year to search from, and “2000” as the number of tweets to scrape. It also prompted me for my preferred filename for the results. I repeated this process for each year until I was able to get curative data on both O2 and BT Telecommunications from 2013 to 2023. 
The script then utilized the snscrape library to search for tweets matching my search queries and within the specified timeframe. As the script searched for tweets, it cleaned each tweet’s content by removing URLs, retweets, hashtags, mentions, and special characters. It also extracted various metadata such as the tweet’s ID, date, user location, user follower count, user following count, whether the user was verified, source of the tweet, number of likes, retweets, and replies.
After the script completed the scraping process, it saved the scraped data to a CSV file with the filename I specified earlier. I was then able to open the CSV file to view the scraped data, as well as proceed with the analysis of scraped data.
The Trenderfly script successfully scraped 2000 tweets related to O2 and BT Telecommunications from the 2013 through 2023. The scraped data included various metadata such as the tweet’s content, ID, date, user location, user follower count, user following count, whether the user  verified, source of the tweet, number of likes, retweets, and replies.



## Research Limitations: 
> The study has some limitations, including the availability and quality of the data collected from online sources. The accuracy of the sentiment analysis tools used in the study may also affect the reliability of the findings.


## Note
> Trenderfly = this is where the code i use to scrape the data is saved
Note: when i finished scrapping the data they were saved in different dataset by year, so i had to merge them together i.e i merge 02 dataset 2013-2023 into one datasets and i also merge BT 2013-2023 into one datasets.

