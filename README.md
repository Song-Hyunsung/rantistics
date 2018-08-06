# rantistics

Rantistics is a data analysis project using Python to scrape 3 data (number of comments, number of upvotes, and word count) from the top 3 post in subreddit /r/rant daily to show any possible relationship with days of week.

The data is scraped from reddit using PRAW and are saved into postgresql database. Weekly data is pulled from postgresql database into pandas dataframe and is plotted using plotly and cufflinks.

This script was ran for the fourth week of July 2018.

In addition to the 3 data the database also holds the actual posts and its content.