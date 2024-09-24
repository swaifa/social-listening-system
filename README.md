# social-listening-system
A social listening system developed using aspect-based sentiment analysis.

A. Dataset Creation
The SN Scrape library was utilized to scrape tweets with a
specific hashtag from Twitter in order to collect the Twitter
dataset. A total of 10000 tweets with the hashtag
“#phonereviews” between January 1st, 2021 and March
24th, 2023 were gathered, and each tweet was stored as a row
in a CSV file containing the tweet's date, ID, and text content.
Following the retrieval of the tweets, data was preprocessed.
Regular expressions were utilized to remove any URLs from
the tweets. In addition, it was observed that some tweets
included URLs pointing to external content, rather than
having text themselves. To address this issue, the contents of
each URL were scraped using the BeautifulSoup library and
the URL in the tweet text was replaced with the scraped text.
The resulting dataset contained a CSV file with the following
columns: 'Datetime' (the timestamp of the tweet), 'Tweet Id'
(the unique identifier of the tweet), and 'Text' (the cleaned and
preprocessed text of the tweet). This dataset was then used
for further analysis and modeling.
The scraper was also used to extract data from Amazon, in
order to enhance it.
