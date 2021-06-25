---
layout: post
title: The Magic Cafe Dataset
categories: datasets 
---

I am an advid reader of The Magic Café, with nearly 13 years browsing thousands of threads ranging from "How to Dress" to "How do I improve my Bottom Deal." I also enjoy magic drama and reading fights between users. 

Most magicians, amateur or professional, know about The Magic Cafe. Steve Brook started The Magic Cafe in 2001 to stay in touch with magic friends {% cite endersgame_2020 %}. At the time of this post, it has been online for 20 years, older than Twitter (2006) and Facebook (2004). How has the community changed over time? Is the community still as active as it was a decade ago? I have scraped the public posts to answer these questions and more.

This post introduces the dataset and includes a summary of the basic statistics. In future posts, I will explore the dataset in more depth. If you want to skip the fluff and jump into the dataset yourself, find the dataset and code below:

Download: [Link](https://drive.google.com/file/d/1H1fNp01wsk8rL16BReMHX6xcr38UeE5Z/view?usp=sharing).

Code: [Link](https://github.com/quantifiedmagic/The-Magic-Cafe-Dataset)

# Basic Statistics

&nbsp;


|---|---|
|Total Threads| 321463 |
|Total Posts| 6029642 |
| Average Posts per Thread| 18.76|

&nbsp;

With more than 300k threads, the dataset is large given the niche community. Moreover, the forum is active, with nearly 19 posts per thread on average. The Magic Café has averaged 300k new posts per year. 

|Subforum|Count|
|---|---|
|The workers | 25534 |
|Penny for your thoughts | 23259 |
|Not very magical, still... | 20599 |
|Latest and Greatest? | 16486|
|Tricks & Effects | 13564|
|Nothing up my sleeve...| 11094|
|The spooky, the mysterious...the bizarre!|10937|
|Our new arrivals|10803
|The little darlings|10329|
|Grand illusion|8638|

&nbsp;

The most popular subforum on the site is "The workers," a subforum dedicated to card magic. Closly trailing card magic is the subforum on mentalism, titled "Penny for your thoughts." The numbers are unsurprising for three reasons. First, online communities do not last for 20 years unless they are active. Second, card magic and mentalism have a special aurora around them with relationships with gambling and simply reading the mind of strangers. Third, this information is accessible by simply summing the numbers available on the site as shown below:

&nbsp;

![The Magic Cafe](/assets/themagiccafe-posts.png){: width="250" }

&nbsp;

But, what else can we do with the dataset that is not accessible on the website's front page? Next, below I answer a few simple questions using the dataset.

## Which thread contains the most posts?

> "Take any card you like..not THAT one!" --Every Magician

Magicians love one liners and hacky premises. This is evident given the longest threads on the website listed below:

|Count|Link|
|-----|----|
|25012 | [The Magic Cafe Forum Index >> Not very magical, still... >> Answer a Question with a Question](https://www.themagiccafe.com/forums/viewtopic.php?topic=250916&amp;forum=32)|
|13703 | [The Magic Cafe Forum Index >> The workers >> Card Trick Game](https://www.themagiccafe.com/forums/viewtopic.php?topic=181702&amp;forum=2) |
|11651| [The Magic Cafe Forum Index >> Not very magical, still... >> New Game: You're Banned](https://www.themagiccafe.com/forums/viewtopic.php?topic=385331&amp;forum=32&amp;start=0) |
| 8620| [The Magic Cafe Forum Index >> Now that’s funny! >> Gag tag](https://www.themagiccafe.com/forums/viewtopic.php?topic=230576&amp;forum=24)|
| 8359| [The Magic Cafe Forum Index >> Now that’s funny! >> Three words  TOPIC IS LOCKED](https://www.themagiccafe.com/forums/viewtopic.php?topic=247474&amp;forum=24)|
| 7884 | [The Magic Cafe Forum Index >> Now that’s funny! >> Give me five](https://www.themagiccafe.com/forums/viewtopic.php?topic=327332&amp;forum=24)|
| 7126| [The Magic Cafe Forum Index >> Not very magical, still... >> Two words...](https://www.themagiccafe.com/forums/viewtopic.php?topic=352338&amp;forum=32)|
| 6652 | [The Magic Cafe Forum Index >> Now that’s funny! >> The alphabet game  TOPIC IS LOCKED](https://www.themagiccafe.com/forums/viewtopic.php?topic=250953&amp;forum=24)|
| 6615| [The Magic Cafe Forum Index >> Now that’s funny!](https://www.themagiccafe.com/forums/viewtopic.php?topic=330272&amp;forum=24)|
| 5281 | [The Magic Cafe Forum Index >> Now that’s funny! >> Why is it that???](https://www.themagiccafe.com/forums/viewtopic.php?topic=278537&amp;forum=24)|

&nbsp;

The longest thread on the forum, "Answer a Question with a Question," has 1,250 pages of content (25k total posts), the post goes on and on and on and on. Go ahead and read each of the popular posts, I'm sure there are gags there that you already use (I know I do).

*Future work: Make an app that shocks me every time I say something that has been said 5 million times.*


&nbsp;

## What is the longest post made on The Magic Café?


# References

{% bibliography --cited %}
