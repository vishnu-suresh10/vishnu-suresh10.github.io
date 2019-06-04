---
layout: project
type: project
image: images/twitter.png
title: Positweet
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2019-04-06
labels:
  - NLP
  - Sentiment Analysis
  - Python
summary: My team developed an application that notified users if they had negative tweets on their twitter account.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/gallery.jpg">
  <img class="ui image" src="../images/gallery-2.jpg">
  <img class="ui image" src="../images/gallery-3.jpg">
</div>

We created Positweet to build and create a more friendly environment online. Negativity impacts the way in which people live their everyday lives. It changes the actions they take and alters their mood to the worst. Our team did not like seeing people like this because we know they are not at their full potential. That is why we created Positweet, a client that manages you comments on Twitter. Positweet can be used two-fold: Users can get notifications about positive replies on their twitter feed. These notifications will go out every hour and will motivate and inspire the user. Positweet can also be used to see if there are negative tweets on you Twitter feed. If there is a negative tweet, it will inform the user through text message, but will not send the contents of the comment. Positweet is a content moderation software for your Twitter feed. First, you enter your phone number and Twitter username. From then on, when someone comments on your latest Tweet, our Python script gets the comments using Twitter's public API and analyzes the sentiment using Google Cloud's natural language processing API. Depending on the preference you select in setting up the software, we will send you a text notification if it is a positive or negative comment. Now you can be fully informed of the sentiments of comments on your Twitter feed! We developed our hack by strategically dividing the work amongst the team members. Using HTML and CSS, Shardul created templates that would later be dynamically accessed. The website created using these templates has a form to register with the service and information about how it works. Additionally, Conor and Vishnu wrote several Python scripts to collect and analyze comments using Twitter and Google Cloud Platform API’s, then send a text accordingly using Twilio. Bringing the two aspects of the project together, Justin used the Flask framework, writing functions that utilized the rest of the group’s work. Ultimately, it was this division of work that enabled us to efficiently and effectively develop our hack.

You can learn more on [Devpost](https://devpost.com/software/positweet-ijdez1).



