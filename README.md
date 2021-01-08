# Sentiment-Analysis
Explored topic modeling and sentiment analysis using nltk package.

Gist of the project:

For years, Newspaper (and other tools of Journalism industry) have availed the power of telling stories to evoke emotions.
Performed Sentiment Analysis and Topic Modeling on the 20 Newsgroup Dataset which contains thousands of newspaper texts or documents.

Idea behind this project is to use:
1) Topic Modeling to find the top 10 topics and their most frequent words
2) Sentiment Analysis to identify which news groups had positive and/or negative sentiments attached to them.

How does the data look?
We have taken the 20 Newsgroup dataset for our experiment.
It is extracted from Usenet bulletin boards, an internet based discussion forum.
Variety in the data: Contains thousands of messages under each topic or newsgroup.
LABELS
Text: Actual message sent 
Newsgroup: Group under which the message is sent

Data Pre-Processing includes:
The Wordcloud plotted helped us to identify the presence of untidy text.

Design Decisions:
Remove email IDs and related keywords (Eg: @, .com, from, header, etc.)
Regex was used to expand contractions (Eg: “\’ve” is converted to “have”)
Double spaces and sequence of "-,*,^,.“ were removed
Lemmatization was performed.
Stopwords were removed (only for top modeling)
