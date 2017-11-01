The input to the program is a file named <twitter_user>.csv. This file has to be generated first by running the excellent program __Exporter.py__ available in the github repository GetOldTweets-python.

To get the tweets csv file of, say @twitter_user from 01-Jan-2015 to 25-Sep-2017, the command is:

```commandline
$ python Exporter.py --twitter_user --since 2015-01-01 --until 2017-09-25
```


The created file has to be renamed to twitter_user.csv. Then run this program as
```commandline
$ python tweets_analysis twitter_user
```

Optional: language for stopwords (default: 'english')
```commandline
$ python tweets_analysis twitter_user language
```

Note: Python3 version (Python2 version in [original repository](https://github.com/mh-github/python-misc))
