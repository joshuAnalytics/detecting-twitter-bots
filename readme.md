# detecting twitter bots

## goal

An experiment in detecting twitter bots (automated accounts) which cluster together using a combination of twitter user metadata and social network analysis metrics generated via graph modelling. 

The goal is to generate an effective input dataset to enable classification of a given twitter user's follower base in terms of human vs bot. 

This could also be applied across thematic hashtag searches to determine the proportion of human vs bot chatter. 

## twitter scripts
* `get_users.ipynb` get data on a list of users (e.g. a labelled botlist)
* `get_followers.ipynb` get data on all followers of a specific twitter user 

## data processing
* `preprocessing.ipynb` concatenate csv files and generate features 

## graph analytics
* loading account_id (source) -> follows_target (target id) pairs into graph and generating Social Network Analysis metrics 

## EXISTING CLASSIFIERS
https://botometer.iuni.iu.edu/#!/
http://dashboard.securingdemocracy.org/
https://botcheck.me/

## THEORY
https://medium.com/dfrlab/botspot-twelve-ways-to-spot-a-bot-aedc7d9c110c

## BOTLISTS
https://www.recode.net/2017/11/2/16598312/russia-twitter-trump-twitter-deactivated-handle-list (all deactivated)

## DOCS
https://developer.twitter.com/en/docs/accounts-and-users/follow-search-get-users/api-reference/get-followers-list
https://developer.twitter.com/en/docs/tweets/data-dictionary/overview/user-object
http://python-twitter.readthedocs.io/en/latest/twitter.html#module-twitter.api
https://networkx.github.io/documentation/stable/reference/index.html

