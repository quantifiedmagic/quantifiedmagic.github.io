---
layout: post
title: Is The Magic Café going to Disappear?
categories: Analysis
date: 2021-06-25 14:57 -0500
---
![disappear](https://media.giphy.com/media/VIzs0jgs8KmgVeTknN/giphy.gif){: width="250"}

Now 20 years old, The Magic Café is a popular community for magicians. Yet, with the popularity of Facebook groups and Reddit (e.g., [r/Magic](https://www.reddit.com/r/Magic/) and [r/CardMagic](https://www.reddit.com/r/cardmagic/)), the old-school design of The Magic Café may turn young magic enthusiasts away from the platform.

There are many signals that the community is declining. For instance, the guest of honor series is no more, which featured magic icons ranging from Eugene Burger to Darwin Ortiz. The last guest of honor was Xavier Spade in 2016 — the only guest that year.

From personal experience, I go months without visiting The Magic Café. Yet, even after six months away, catching up is easy. In contrast, keeping up with posts on Reddit is more difficult.

Is the volume of posts decreasing over time? Are certain areas of magic declining more than others? Is the Magic Café dying? In this post, I examine these questions and more.

As always, find the code and the data linked below:

Dataset: [Link](https://quantifiedmagic.com/datasets/2021/06/24/the-magic-cafe.html)

Code: [Link](https://github.com/quantifiedmagic/Blog-Analysis-Notebooks/tree/master/analysis/is-the-magic-cafe-going-to-disappear)

# Posts, Posts, and more Posts

![The Magic Cafe](/assets/posts/is-the-magic-cafe-dying/magic-cafe-time.png){: width="500" }

There you have it. The number of posts is dropping year after year, starting in 2008. Why did it begin declining in 2008? The housing crisis? Competition from other magic communities ranging from Reddit to Theory11? Who knows. Given the drop in the number of posts, it is unsurprising that special guests stopped in 2016. Why would guests appear if there is no one to speak to? There are other online magic communities (e.g., [Genii Magazine's forum](https://forums.geniimagazine.com/)), and many have been around as long as The Magic Café. Therefore, competition may not be the only reason.

# Post frequency and Magic Genre

Are all magic genres (e.g., cards, mentalisim, etc.) declining at similar rates? I find that the distribution (shape) of the decline varies genre-to-genre. For instance, has mentalism (the "Penny for your thoughts" page) combated the max exodus better than the card magic group (The workers)? See the figures below:

![The Magic Cafe](/assets/posts/is-the-magic-cafe-dying/workers-time.png){: width="500" }

"The workers" (card magic) subforum's decline started in 2004, much earlier than the overall decline of the Café (which began in 2008). This finding is intriguing. I tried to look at posts around that time to see what happened but could not gather anything quickly. Did the moderation methods change? Did the forum become saturated such that searching for old posts replaced the need to post new ones? One way to answer these questions is qualitative analysis, surveying forum moderators and frequent users at that time to understand what changed. If this topic excites me in the future, I will reach out and see if I can gain insight into the decline.

![The Magic Cafe](/assets/posts/is-the-magic-cafe-dying/mental-time.png){: width="500" }

In contrast, the shape of the decline for the mentalism subforum is much different than card magic. The decline better matches the overall distribution, with a drop in posts starting in 2007.


![The Magic Cafe](/assets/posts/is-the-magic-cafe-dying/bus-time.png){: width="500" }

The "Tricky Business" subforum (which "talk(s) about the business side of magic") also declined over time. The forum did see a substantial resurgence in 2011 (which also appeared for the previous two communities, albeit much smaller). But, now averages only a few posts each day.

Overall, while the rate is not entirely the same for each genre, one this is for sure, all parts of The Magic Café forums are declining.

# Are users leaving or posting less often? 


![The Magic Cafe](/assets/posts/is-the-magic-cafe-dying/nunique_users.png){: width="500" }

How many active users are there each year? I define active users as users that posted at least once on the forum. At the peak of The Magic Café's popularity, around seven thousand unique users were posting each year. In 2020, there were less than four thousand individual users, less than the total activity in 2003. Interestingly, the number of active users dropped much slower than the number of posts per year. I assume many users were like myself, visiting every few months. But, as activity is dwindling, there is less content to explore. Thus, there is little motivation to continue visiting.

So, what does the decline in user activity mean? As an outsider, I can only speculate. Specifically, I think there are two aspects at play. First, other magic discussion platforms (e.g., r/Magic) are eating up potential users. Second, I'm reminded of a quote from Max Maven's book (Prism: The color series of mentalism) that states, "*Mentalism, like many things employed for human entertainment, goes through cycles of popularity*." I think this statement applies to magic interests in general. The early 2000s to 2010 was a "boom" period for magic, potentially caused by television shows like Criss Angel Mindfreak that ran from 2005 to 2010, or other reasons. Whatever the reason, The Magic Café community still has enough activity to continue for a long time. But, given Steve Brook's recent [personal crisis](https://www.themagiccafe.com/forums/viewtopic.php?topic=723763) and the fast decline in user activity, the need to document this piece of magic history is essential before it disappears forever. I hope to update The Magic Café Dataset biannually to keep a copy around if anything were to happen.

# Other interesting findings

Okay Okay Okay... Enough with the apocalyptic study about the end of The Magic Café. The plots below show a couple interesting trends.

![The Magic Cafe](/assets/posts/is-the-magic-cafe-dying/magiccafe-days.png){: width="500" }

**What day of the week do people post most often?** Not the weekend. It seems that many magic aficionados prefer to post on duty (during the work week).

![The Magic Cafe](/assets/posts/is-the-magic-cafe-dying/magiccafe-month.png){: width="500" }

**What month people post most often?** January. After a hectic time with family or inlaws, spending time staring at yourself practice your classic pass seems to be the best way to relax.

# Conclusion

Is the popularity of The Magic Café declining? Yes. I don't know where exactly the magic community has moved to. But, in future work, I hope to contrast other communities' growth and decline rates to better understand the situation.
   For now, check out The Magic Café, see what is going on. Who knows, maybe it will see a successful resurgence soon.

