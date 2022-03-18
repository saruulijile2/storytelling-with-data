# Project information

Comparison between the manual and artificial sentiment analysis of the Twitter reaction towards different cast members of “90 Day Fiance.” The team consists of Akiah Watts (AkiahW) and Saruul (Saruulijile2).

# Overview

We conducted sentiment analysis on the cast of the TV show called “90 Day Fiance” using public tweets. The show matches US citizens with foreigners who want to get a Green Card and live in the States permanently. We chose Big Ed, Rose, and Lis as they sparked lots of online discussions and attracted great amount of attention from the public. First, we assumed that the public sentiment towards Rose would be sympathetic because of how Ed treated and lied to her throughout the show. Then, we also thought the public opinion will be mostly negative toward Ed with people disliking his treatment of others and making fun of him. Lastly, we assumed that the public opinion will be negative toward Liz, Big Ed’s wife, because she continues to endure his mistreatment instead of leaving like Rose. To conduct the sentiment analysis, we first started by using the Twitter’s advanced search feature and manually collected and analyzed the valence of the tweets. Then we also used an artificial analysis tool, which we predicted to result in overcalculating the neutral valence tweets. Overall, the artificial analysis for all the three cast members found the most common valence of the tweets were neutral, supporting our hypothesis. Our manual analysis for Ed and Rose also found more neutral valence, but Liz’s manual analysis found more negative tweets. Moreover, the categories of the tweets differed greatly for each cast member. Tweets under the category of “funny” and “reaction” were most common for Rose while “dislike” was the most common category for Liz. 

YouTube Link: https://youtu.be/1PMJXTkK_Dg

# Downloading the data

Dataset of Rose tweets
Rose: https://github.com/ContextLab/storytelling-with-data/blob/master/data-stories/Ed-nalysis/Rose.csv

Dataset of Ed tweets
Ed: https://github.com/ContextLab/storytelling-with-data/blob/master/data-stories/Ed-nalysis/Ed-nalysis%20-%20Ed.csv

Dataset of Liz tweets
Liz: https://github.com/ContextLab/storytelling-with-data/blob/master/data-stories/Ed-nalysis/Liz.csv

# Running the code

Start by running the setup (outside libraries required for visualizing the data) and data (the aforementioned tweets). The spreadsheets include the tweets, and human analysis of the valence and category the tweet would fall under. Under the Analysis section, we first visualized the categories of the tweets for each cast member. These tweets were put into categories such “dislike” and “funny” manually. Then, we moved on to manually and artificially analyzing the valence of the tweets for each cast member, and we also visualized our comparison of the two analysis. Lastly, we created word clouds that showed the most common words in the tweets of each cast member of the show.  

# Contributing to the code

Some next steps would be filtering tweets within the time range of the show to get more reaction quotes and changing search word to the spinoff series to get more tweets about the characters.

# Acknowledgements

My lovely boyfriend and CS major Robert for debugging and helping with the construction of the first bar graph. 
