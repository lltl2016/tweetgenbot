# tweetgenbot
Amber and Lang's Collective Intelligence Final Project 

genbot is an interactive twitter bot that uses direct messaging and neural networks to generate original messages based off tweets on a topic supplied by the user. This project was all written in rstudio. genbot can be found at @tweetgenbot on twitter.

genbot's code has two components: the twitter functionality and the RNN generative code. The former uses functions of the twitteR and rtweet packages, the latter uses keras and tensorflow. <i>integrated genbot</i> is what genbot uses, but if you want to make an interactive bot that does something else, or want to generate text from somewhere other than twitter, you can see what code is relevant to only those tasks in <i>genbot code</i> and <i>RNN model</i>. 

<i>tweetText.txt</i> is a small file of 1000 tweets that was used for testing purposes (extracting/cleaning/passing in tweets, data for the RNN code). The keyword used on the search was "kittens".
