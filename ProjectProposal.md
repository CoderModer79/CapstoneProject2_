The problem :

*Twitter Sentiment Analysis over 13 Feelings*

In the past decade, new forms of communication, such as text messaging
have emerged. While there is no limit to the range of information conveyed by tweets and texts, often these short messages are used to share opinions and sentiments that people have about what is going on in the world around them.

Working with these informal text genres presents challenges for natural language processing
beyond those typically encountered when working with more traditional text genres, such as newswire
data. Tweets and texts are short: a sentence or a headline rather than a document. The language used
is very informal, with creative spelling and punctuation, misspellings, slang, new words, URLs, and genrespecific
terminology and abbreviations, such as, RT for “re-tweet” and #hashtags, which are a type of
tagging for Twitter messages. How to handle such challenges so as to automatically mine and
understand the opinions and sentiments that people are communicating has only very recently been the
subject of research.

We believe that a freely available, annotated corpus that can be used as a common testbed is
needed in order to promote research that will lead to a better understanding of how sentiment is
conveyed in tweets and texts. Our primary goal in this task is to create such a resource: a corpus of
tweets and texts with sentiment expressions.

Sentiment Analysis- Emotion in Text In a variation on the popular task of sentiment analysis, this dataset contains labels for the emotional content (such as happiness, sadness, and anger) of texts. 40.000 samples across 13 labels.

*The Client:*

**Businesses/ Organizations**

Sentiment analysis has many applications and benefits to any business and organization. It can be used to give valuable insights to the business regarding how people feel about your product brand or service.

**Product Advocates/ Social Media Influencers**

When applied to social media channels, it can be used to identify spikes in sentiment, thereby allowing someone to identify potential product advocates or social media influencers.

It can be used to identify when potential negative threads are emerging online regarding your business, thereby allowing you to be proactive in dealing with it more quickly.

**Corporate Network**

Sentiment analysis could also be applied to the corporate network, for example, by applying it to its email server, emails could be monitored for their general “tone”.  For example, Tone Detector is an Outlook Add-in that determines the “tone” of your email as you type.  Like an emotional spell checker for all of your outgoing email.

*Data Set:*

- Taken from : https://data.world/crowdflower/sentiment-analysis-in-text

- Data Set includes 4 features and 40.000 data points/samples.

- This data comes from 2016. By means of APIs, we can collect fresh data from 2017 and 2018.

*Approach:*

- This is a supervised problem. Target Feature will be 'sentiment'. Since this feature has 13 labels, solution would be multi labe classification problem, or other approach might be a regression.

- To be able to pre-process the data, I will use NLP methods on the content.
