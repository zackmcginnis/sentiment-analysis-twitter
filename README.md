Twitter Sentiment Analysis
===============

Summary
-------------------
Python3
This simple application prints the general sentiment (using polarity and subjectivity, where -1 < polarity < 1 and 0 < subjectivity < 1) of a specified string on Twitter.
This is accomplished using the Twitter API and the textblob library for sentiment analysis.

Getting Started
-------------------
All of the needed libraries can be installed using `pip install -r requirements.txt` in the repository directory.

You will need to register with Twitter's API in order to obtain your token and make API calls.  Once registered, create a `config.py` file and place the appropriate token/values in an object:
`
# config.py
API_CONFIG = {
    'consumer_key' : 'fake_key',
    'consumer_secret' : 'fake_secret',
    'access_token' : 'fake_token',
    'access_token_secret' : 'fake_token_secret'
}
`

Run the script using `python twitter-sentiment-analysis.py`.
Note: On windows, you may receive a charmap/codec error. This can be resolved by running `chcp 65001`
