# MTweet

A collection of 13,150 tweets on Machine Translation (MT). All tweets
* were created between 1 Jan 2015 and 31 Jul 2017, and
* contain the string ‘machine translation’ and/or ‘machine translated’.

We provide id (`id`), timestamp (`created_at`), full text (`text`), and polarity (see below) for each tweet.

### Sentiment Analysis

All tweets come with polarity labels, where
* `1` denotes positive tweets,
* `2` denotes neutral tweets, and
* `3` denotes negative tweets.

Labels in the `automatic` column were assigned by an automatic sentiment classifier ([Baziotis et al., 2017](http://www.aclweb.org/anthology/S17-2126)) trained on 50,000 tweets not related to MT (i.e., the SemEval 2017 training data; see [Rosenthal et al., 2017](http://www.aclweb.org/anthology/S17-2088)).

Labels in the `human_A` and `human_B` columns were assigned by two independent human judges. Human judgements are available for 150 tweets in this collection.

For details on data collection, filtering, and classification, please have a look at our [paper](#todo).

### Reference

If you use any of the data provided here, please reference the following paper:

```
@inproceedings{mtweet,
  Author = {L\"{a}ubli, Samuel and Orrego-Carmona, David},
  Title = {When Google Translate is better than some human colleagues, those people are no longer colleagues},
  Year = {2017},
  Booktitle = {Proceedings of the 39th Conference on Translating and the Computer},
  Address = {London, UK},
  Month = {November}}
```

### Important Note

While we share this data directly for you to use without downloading full texts from Twitter, it is your responsibility to maintain Twitter's [Terms of Service](https://twitter.com/tos) and to delete tweets that are no longer public.
