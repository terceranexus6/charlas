---
title: Digital context behind revolution
published: false
description: The digital repercussion in the first of October in Spain, and how this makes me wonder about international internet censorship and digital rights issues.  
tags: Networks, social, domain, digital, censorship 
—-

I'm not very comfortable speaking about politics, And I won't, as this is not the place to write about it. But I got very interested in the digital role of yesterday. Please! **I completely discourage political comments**, I'm just trying to create a technical analysis, and this is a technology blog!

For the ones who are lost in the context, I will shortly explain before starting the digital analysis: Catalunya is legally part of Spain, but some of the inhabitants have expressed their desire of being independent. Our constitution states that such an act is not possible, so the steps for allowing this should be changing the constitution under the responsibility of the maximum political parties, create a referendum for letting people vote in such statement, and proceed the result of it. Unfortunately, tensions in Spain lead in an "_illegal_" referendum (as the constitution wasn't changed) and a brutal response from the government against civilians. This would be the short introduction.

**Now, what do I mean with the digital role in this context?**

**Social Networks** meant a significant role in this situation. But also did some details that played with users liberties here. First of all, let's go back a few days, when some webpages of .CAT domain where banned, moreover a .cat domain crackdown was established. Regardless the legal limits this takes, This meant concerns of the users from all Spain, as even if we don't usually check this pages, this meant the oversized control on the internet, [as the EFF explained](https://www.eff.org/es/deeplinks/2017/09/cat-domain-casualty-catalonian-independence-crackdown). This already created a digital concern in users, and some significant characters in the Internet defense (apart from the already mentioned organization) such as _Julian Assange_, shared opinions. Whatever the reader agrees or not with the journalist opinion, the scope of the public opinion lead in a brand new, global dimension of an internal issue. 

**Internet Freedom** is an important right every user should ask for. We (as spaniards) usually get surprised when are told about seizure of the internet in [China](http://12mars.rsf.org/2014-en/2014/03/10/china-electronic-great-wall-getting-taller/), [Russia](http://12mars.rsf.org/2014-en/2014/03/11/russia-repression-from-the-top-down/), [Iran](http://hyperakt.com/items/archived/iran-censorship-infographic/) and [other countries](http://12mars.rsf.org/2014-en/) and surely our case is not as astonishing to the date, but the main problem is not the size of the issue right now, but what can be laid in the future if such banning is, let's say, _socially_ allowed (alongside other digital problems we are facing since long time ago such as the gag-law) and, the more I investigate about it, the more I find about every country affair with internet censorship. Maybe letting the rest of the world judge our situation is dangerous, as we are exposed to misunderstanding, comments without the right context and, why not, huge shame. But seeing myself in the context spotted in the eyehole of international journalism makes me think about our own perspective of internet censorship and digital issues that _others_ (meaning foreign countries) are facing.

On the other side there's the **decentralized movement** on the internet. Not long ago, in my city in the south of Spain, there was huge demonstration asking for good health resources. I was particularly surprised that time, as thousands of neighbours came along to demonstrate regardless the age or social condition. Apparently the demonstration was announced in different social media, and everyone got the message, literally everyone! This time, is not different. Even though television was emitting the event, thousands of users were following it from social media (including myself), in my case, and probably in the case of many spaniards and foreigners, looking for a decentralized source of information (in my opinion, more reliable). This means an uncomfortable position for the journalism, the huge question they used to protect themselves at dangerous situations, for example, was "_Who's gonna tell your story if you attack me?_" and now the answer is quite easy "**_myself_**". Now technology let the users be both readers and writers, not meaning anyone can be as eloquent or organized as a real journalist, but surely anyone is a potentially information node.

Changes in the government has always been a requirement of civilians in different eras, and each time had their ways of communication. The relevant point in our current world is the leading, [fast and huge amount of information generated everyday](http://www.internetlivestats.com/), and specially in difficult situations worldwide. Obviously controlling that amount of information is _technically_ impossible, although leading opinions can still be _manipulated_. The ways an user can be attacked in this situation we faced yesterday are:

- **Internet Shutdowns**, which are said that happened, but actually was an internet connection overload, that was covered with volunteers mobile hotspots. 

- **Leading nodes manipulation**, in social media there are what I like to say "leading nodes", influential users that reach lot's of people in a certain network (let's say, politicians, famous characters and such) and their opinion can give voice to others. If a certain group of these nodes is manipulated, so is a portion of their nets.  

**And against those, an user can defend itself with several strategies.**

- Having a well thought, reliable source of information nodes. This means having at hand _nodes_ of different opinions and lot's of nodes, which allows the user to have a big picture of every situation. 
- Posting with common sense and cold mind, avoiding posting something the user might regret later, which can lead in tagging the user as not a reliable source by other users. This could give us a chance to participate meaningfully in something we care about.
- Having at hand proxies, VPN, and alternative ways of communication, to avoid being shut down in an important situation. In [this guide](https://ssd.eff.org/en) there's more about it.

**And what can we do as developers?**

And what can we do as developers?

As developers we also have a certain role in this frame. First of all the knowledge of this amount of data gives us the opportunity of doing a deep study in Big Data. I have my doubts in Big Data, as it can lead in dangerous practises against users' privacy, but let's give a chance to a healthy data study. There are several tools on the internet to collect networks information. I would give a chance to Python here, using for example [Tweepy repository](https://github.com/tweepy/tweepy) to create an [API for twitter](https://apps.twitter.com/) stats. Be careful as many [famous examples](http://www.tweetchup.com/es) on the internet are not updated. If you create a significant user-friendly app I suggest letting the users in difficult politics situations, use it for free (meaning free also data free, without login, for privacy support) but this is only a personal appreciation.

I suggest also using [this page](http://analytics.followthehashtag.com) to get hashtag content, and use [gnuplot](http://lowrank.net/gnuplot/datafile-e.html) to transform this data into graphics for a fast, not so difficult homemade Data analysis.

![](https://github.com/terceranexus6/cosicas/blob/master/images/datatwitter2.jpg)
![](https://github.com/terceranexus6/cosicas/blob/master/images/datatwitter.jpg)

(last one is created with gnuplot using data from the web of tweets per minute in the range of 10:00-10:30-11:00)

To sum up, everyone has a role in the digital world, and last century's technology can lead in a different way of world strategies, politics and demonstrations. Controlling this kind of information techniques might let us understand our world better and our role as developers is indispensable. 
