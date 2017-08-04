# hashtag adoption time series

The dataset released here has been used in our paper "#Bigbirds Never Die: Understanding Social Dynamics of Emergent Hashtags." [link to the paper](https://www.aaai.org/ocs/index.php/ICWSM/ICWSM13/paper/view/6083/6376)

In this study, we examine the growth, survival, and context of over 250 novel hashtags during the 2012 U.S. presidential debates. Our analysis reveals the trajectories of hashtag use fall into two distinct classes: "winners" that emerge more quickly and are sustained for longer periods of time than other "also-rans" hashtags. Statistical analyses of the growth and persistence of hashtags reveal novel relationships between the hashtags' contextual features and the relative success of hashtags. This is the first study on the lifecycle of hashtag adoption and use in response to purely exogenous shocks, which has implications for understanding social influence and collective action in social media more generally.

The dataset was the hashtag adoption time sequences during the four debates. They are used to create **Figure 1** in the paper  (Cumulative tweet volume of hashtags over time, starting from each debate). 

Each csv file has three columns:
time (in UTC), y (the minute-by-minute cumulative tweet count), and tag (the hashtag name).

The onset of the four debates are:
Debate 1: 2012-10-04 00:00:00 UTC
Debate 2: 2012-10-12 00:00:00 UTC
Debate 3: 2012-10-17 00:00:00 UTC
Debate 4: 2012-10-23 00:00:00 UTC

The raw tweet data have been released via the ICWSM Data Sharing Service. See: 
[http://www.icwsm.org/2013/datasets/datasets/](http://www.icwsm.org/2013/datasets/datasets/)

## Publication
If you make use of these data sets and code, please cite:

Lin, Y.-R., Margolin, D., Keegan, B., Baronchelli, A., Lazer, D. (2013). #Bigbirds Never Die: Understanding Social Dynamics of Emergent Hashtags. In Proceedings of the 7th International AAAI Conference on Weblogs and Social Media (ICWSM 2013) 