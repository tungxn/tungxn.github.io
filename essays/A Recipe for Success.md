---
layout: essay
type: essay
title: "A Recipe for Success"
# All dates must be YYYY-MM-DD format!
date: 2023-04-27
published: true
labels:
  - Design Patterns
  - Ohana Schoolars
---

<img width="300px" class="rounded float-start pe-4" src="../img/recipes-pic.jpg">

# A Recipe for Success
For me, design patterns are a lot like cooking recipes. Way back in the beginning, our predecessors would eat the animals or plants that they hunted and gathered raw. This is not only very energy inefficient, as raw meat takes more time and energy to break down than the cooked meat we eat today, but it is also dangerous because of the risk of getting sick and possibly dying from bacteria and parasites on the meat. Over time, people began to experiment with their meals. Maybe the caveman was looking to try out new ways of eating because he was bored. Or maybe it was a result of accidentally leaving meat too close to the fire, forgetting it, eating it anyway, and finding it way more delicious than eating it raw (I can only assume as I have never tried meat raw). Afterward, he would tell his friends and thus the first recipe was born. 
To me, this process mirrors the early days of designing patterns for software development because it requires a lot of trial and error. One example is fermentation as a failure would not only result in frustration but with sickness from the bacteria, all the while stumbling around not knowing how fermentation works. 
As more generations pass, more and more recipes are created each improved upon more and more. Bad recipes are forgotten either because the ingredients required are impractical or because some other recipes just taste better. Both of these attributes of recipes are also in design patterns. As time passes, there are more good designs, and improvements are made while bad designs get replaced. 
Another similarity is that both recipes and design patterns help beginners. Instead of going through trial and error, you could learn from the success of your predecessors and use it to create a new food or software. 

# Observer Design Pattern
One example of a design pattern that is used in my project Ohana Scholars is the observer design pattern by using Meteor’s publication and subscription model. An observer design pattern can be thought of as a newspaper subscription service where the data being published in the newspaper and the user is the customer that bought the subscription. In our code, various data can “publish” themselves, and depending on the users’ roles, they can gain access to different sets of data by “subscribing” to it. Whenever the data changes, it will notify all the users subscribing to the data and change the UI to match the data being published.

