# Overview

This is a data analysis site looking into Critical Role, season two, as an example of DnD podcasts. It looks into the player rolls and podcast transcripts to extract insights about how the two effect each other. It was a super instructive practice in analyzing textual data, processing data with pandas and displaying it with plotly express.

Podcast transcripts were collected by [MATHEUS DE ALBUQUERQUE](https://www.kaggle.com/matheusdalbuquerque) and posted on [Kaggle.com](https://www.kaggle.com/). Additional data on dice rolls was collected by the Critical Rol community and posted on [CritRoleStats.com](https://www.critrolestats.com/).

I wrote this software to see if there was a discernable link between the transcripts of a dnd episode and the average dice rolls of the players. I measured the average rolls, the instances of maximum and minumum rolls (natural 1s and natural 20s) and compared them to frequency of swear words and overall posivite/negative and subjective/objective each episode.

[Software Demo Video](https://youtu.be/KQMewDTV7sM)

# Data Analysis Results

Do Lower/Higher rolls cause the players to swear more? - Yes, but only not in the way expected. 
    Overall dice rolls had little corrilation with swearing frequency but Nat1s and Nat20s had a minor positive relationship with the swearing in an episode.
Do Lower/Higher rolls change the sentiment of the episode? Does the language become negative/positive? 
    In the same way, Nat20s and Nat 1s seem to correlate to more negative sentiment in the episode overall.
How does the language change over the season?
    Subjectivity had the most noticeable change over the season, likely as player's parts increased in ratio to the DM.

# Development Environment

The program was developed with a lot of different libraries for text processsing, data handling, chart rendering and more. Libraries include: nltk, collections, pandas, numpy, and plotlyExpress.

# Useful Websites

{Make a list of websites that you found helpful in this project}
* [Pandas Documentation](https://pandas.pydata.org/docs/)
* [Towards Data Science - text sentiment explanation](https://towardsdatascience.com/my-absolute-go-to-for-sentiment-analysis-textblob-3ac3a11d524#:~:text=Subjectivity%20quantifies%20the%20amount%20of,looking%20at%20the%20'intensity'.)

# Future Work

There is still lots of data that could be extracted from the script
* First, there are time stamps by each dice roll, if it were possible to match that up to the specific timing on the scripts, the data would be a lot more fruitful and give many more valueable insights
* There is an opportunity to use the scripts for Ai data generation. For instance, it might be interesting to see how accurately you could make an Ai bot in Matt Mercer's same tone and with his same worldbuilding.
* There might be additional insights from attaching alternate data. For instance, it might be interesting to see how dice rolls affect user interaction with the livestream in twitch, if that data could also be procured.