# Project Proposal: Determining Online Article Accuracy compared to Link Title. (Clickbait detection)

I am interested in determining if there is a way of predicting if an online article link is clickbait based on the structure and usage of the title.

This is interesting to me because learning to sift through the deluge of information in the modern world is rapidly becoming a required skill and determining truth in phrasing is important in both artifical intelligence as well as maximizing a person's precious time.

I would like to know if:

1. There is a particular pattern used to mask clickbat - this implies that we as humans have a pre-desposition to certain communication patterns.
2. If article sources can be assigned a co-efficient, implying that we can rank article sources by "trustworthiness"
3. Which cognitive distortions/logical fallicies are most exploited in the creation of clickbait.

To do this, we need three groups of data sources:

1. Truth control: This is a group of article sources that are considered to be telling the truth
2. Liar control: This is a group of articles sources that are considered to be misrepresenting the truth
3. Variable: This is the group of article sources that we will be comparing against the prior two to determine their "trustworthiness"

For the *truth control group* I intend to use articles from:

* The New York Times (Article Search)[http://developer.nytimes.com/docs/read/article_search_api_v2] and (Most Popular Listings)[http://developer.nytimes.com/docs/most_popular_api/]
* The US Governments Open Data portal (Climate Reports)[https://www.data.gov/climate/]
* Wikipedia Page Traffic Statistics (From the last 3 months)[http://aws.amazon.com/datasets/wikipedia-page-traffic-statistic-v3/]
* Reddit's (Not The Onion Subreddit)[https://www.reddit.com/r/nottheonion/]

For the *variable group*, I will compare and analyze:
* (Mashable)[http://mashable.com/]
* (UpWorthy)[https://www.upworthy.com/]
* (Vox)[http://www.vox.com/]
* (BBC)[http://www.bbc.com/news]

For the *liar control group* I inted to use articles from:
* The Onion (Politics Section)[http://www.theonion.com/section/politics/]
* Reddit's (Fake News Subreddit)[https://www.reddit.com/r/fakenews/]
* The (Daily Currant)[http://dailycurrant.com/]
* The (National Report)[http://nationalreport.net/]

Further sources can be taken from this list on (Fake News Watch)[http://www.fakenewswatch.com/]

Consideration is also made for Comparing Kickstarter pitches to their article content, against their success:
http://webrobots.io/kickstarter-datasets/

