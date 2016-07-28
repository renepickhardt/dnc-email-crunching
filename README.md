This IPython Notebook contains a code block from [Alain Spineux for parsing emails](http://blog.magiksys.net/parsing-email-using-python-content) and then some data processing code from me to extract two social network graphs from [the Democratic National Committee Email Corpus that has been published last week via Wikileaks](https://www.wikileaks.org/dnc-emails/).

The networks are a temporal network of who send emails to whom and a co-recipient network creating a weighted edge counting how often people have been together in CC of the sent emails.

##Usage
========
Install anaconda or any other way to use IPython notebook with Python 2.7 and matplotlib

In the first code block change the directory to the email directory of the DNC corpus that you have crawled

To get the crawled dataset
```
python crawler.py > crawl.sh
chmod a+x crawl.sh
./crawl.sh
```


##License
=======

Alains code is available under LGPL and my code is available under GPLv3

###Blogpost
========

There is a Blogpost explaining a little bit more. Visit: http://www.rene-pickhardt.de/extracting-2-social-network-graphs-from-the-democratic-national-committee-email-corpus-on-wikileaks