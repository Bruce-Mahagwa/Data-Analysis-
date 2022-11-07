# TWITTER_ARCHIVE DATASET
This dataset contains close to 5000 rows of tweet-related data obtained from the twitter API tweepy.
The primary goal was to perform wrangling acts and possibly obtains some insights into the dataset.
Here are the main questions:
1. Is there a correlation between retweet_counts and favorite count. In other words, if a tweet gets many retweets does it also receive a higher favorite count?
2. Is there a positive correlation between a high rating numerator and favorite count.
3. Lastly, we can investigate which dog names were most popular in the database.
The analysis carried out revealed that there is indeed a strong positive correlation between retweet_count and favorite_count. The visualization above proves this hypotheses. This implies that if a certain tweet has many retweets from different viewers then it correspondingly has a higher favorite count. Thus, twitter posts which are most appealing and engaging to viewers usually have more retweets.
The second area of analysis was in trying to determine whether rating denominator was higher for tweets with a high value for favorite count. I expected that there ought to be a strong positive correlation and this was accurate. Favorite count does have a strong effect on the rating numerator for different tweets. This means that viewers who consider a tweet as a favorite provide it with a higher numerator rating.
The last question was frivolous and it sought to discover which name was most popular in the database. I found that there were eleven instances of the namme Charles and this was the most popular name for dogs. The efforts to answer this question were however hampered by the fact that there were many None values in the dataframe. My attempts to remedy this issue proved unfruitful but I am content to select Charles as the most popular name for dogs.

