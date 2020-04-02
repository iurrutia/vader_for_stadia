README


---

## Contents

[1. Overview](#overview)

[2. Model](#model)

[3. Some interesting findings](#disc)

---

# <a name="overview">Overview</a>

The projects looks at reddit threads from the Stadia subreddit to do a sentiment analysis of reddit comments, and look at the words most commonly associated to positive and negative discussion threads.

The notebook can be found here: 

[Link to notebook](https://github.com/iurrutia/MiniMLProjects/blob/master/TestingRedditAnalysis.ipynb)

# <a name="model">Model</a>

I used VADER for reddit thread sentiment analysis. After substituting out game titles (e.g. "Doom", "Red Dead Redemption", "Gods & Monsters") for random character strings, Vader was able to assign a sentiment label to roughly half of the thread titles:


<img src="https://github.com/iurrutia/MiniMLProjects/blob/master/images/classfreq.png" width="400">

# <a name="disc">Some interesting findings</a>

Here are the wordclouds and most frequent words associated with positive and negative sentiments:

## Positive:

<img src="https://github.com/iurrutia/MiniMLProjects/blob/master/images/pos.png" width="400">

Interesting words that most frequestly appeared in positive titles included:
- controller
- support
- games
- free
- play
- friends



## Negative:

<img src="https://github.com/iurrutia/MiniMLProjects/blob/master/images/neg.png" width="400">

Interesting words that most frequestly appeared in negative titles included:
- lag
- latency
- founders
- launch






Future work would look for topic clusters and run this approach on more data.