# Newspaper topic modelling

This project provides the users an ability to understand the trending news topics from a given timeframe by clustering popular keywords.

The user can provide the start and end date and could specify a list of web news domains whcih he is interested in. The user could use this feature to analyze news from say different countries or from diffetent kinds of websites (example technology vs political).

The code uses bow LDA algorithm for topic modelling. The news articles are extracted from the commoncrawl news archives. The code uses newsplease library to extract the articles from the archive. Some of the original files from the library had to be modified and have been included. The graphs are plotted using pyLDAvis library.

Some of the example results can be found under result images directory. Note that these resuls have been obtained for a single day and for a single news source(nytimes)
