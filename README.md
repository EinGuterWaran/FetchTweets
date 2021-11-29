# FetchTweets
Fetch a user's best tweets using the API and save them to a CSV file.

## How to use
If you want to use this repository as a submodule, don't forget to put **credentials.py** in your working directory.  
The essential function is **def tweets_to_csv(username, last_x_tweets, min_favs)**.
* *username*: The Twitter username
* *last_x_tweets*: The how much last x tweets are to be inspected?
* *min_favs*: What is the minimum number of likes a tweet must have to make it into the csv file?
