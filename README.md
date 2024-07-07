# StockPulse
This project analyzes news articles related to stock market trends. It leverages web scraping, text summarization, and sentiment analysis to provide insights into market sentiment and potential stock movements.

* News Scraping: Fetches news articles from various online sources using BeautifulSoup.
* Text Summarization: Condenses the extracted news articles into concise summaries, allowing users to quickly grasp the key points. This is done using the pretrained Pegasus model. 
* Sentiment Analysis: Analyzes the sentiment of the summarized news articles, identifying whether they are positive, negative, or neutral towards specific stocks using version of ROBERTa model trained on financial news data.