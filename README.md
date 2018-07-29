# rantistics

Rantistics is a data analysis project using Python to scrape 3 data (number of comments, number of upvotes, and word count) from the top 3 post in subreddit /r/rant daily to show any possible relationship with days of week.

The data is scraped from reddit using PRAW and are saved into postgresql database. Weekly data is pulled from postgresql database into pandas dataframe and is plotted using plotly and cufflinks.

Currently this project is offline

Later, this project will be online using heroku with daily script to scrape data from reddit with feature to select a week for data analysis and a feature to see the scraped post.
