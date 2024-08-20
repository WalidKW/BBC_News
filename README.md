# BBC_News

![News](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSajL0m36xadXYCJsSZIW4deB8CgJFNpLAbpw&s)

# About Dataset:
### Context
Self updating dataset. It collects RSS Feeds from BBC News using a Kernel: https://www.kaggle.com/gpreda/bbc-news-rss-feeds.
The Kernel is run with a fixed frequency and the dataset is updated using the output of the Notebook.

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

### Content
BBC News RSS Feeds. The data contains the following columns:

1 - title
2 - pubDate
3 - guid
4 - link
5 - description

### Collection method
Uses requests_html and BeautifulSoup to collect RSS Feeds from BBC News site.

### Acknowledgements
The content is proprietary of BBC.

### Inspiration
Use the data to analyze the sentiment of news, from title and description.
