---
layout: post
title: "babydata 04 blog post bottle feedings"
gif: assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_3.gif
date: 2017-08-22
---

We had a baby! Toby Lev Letourneau was born April 13th 2017, and he\[CloseCurlyQuote]s such a cool kid.

![babydata-04-blog-post-bottle-feedings_2.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_2.gif)

![babydata-04-blog-post-bottle-feedings_3.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_3.gif)

We\[CloseCurlyQuote]ve been tracking Toby\[CloseCurlyQuote]s bottle feedings using an app called BabyConnect since he was born. We track when we gave him a bottle and how much he ate. It\[CloseCurlyQuote]s been immediately useful to know exactly when we last fed him, since babies have to eat very frequently when they\[CloseCurlyQuote]re first born to maintain their blood sugars. We\[CloseCurlyQuote]ve seen the occasional food coma:

![babydata-04-blog-post-bottle-feedings_5.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_5.gif)

![babydata-04-blog-post-bottle-feedings_6.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_6.gif)

A nice side-effect of tracking Toby\[CloseCurlyQuote]s bottle feedings is the database we\[CloseCurlyQuote]ve created of his eating habits over time. Toby\[CloseCurlyQuote]s about 4 months old now, so we have about 4 months of data to show how his eating habits have progressed.

This goal of this post is to explore the data a bit!

I exported a CSV file from BabyConnect:

![babydata-04-blog-post-bottle-feedings_10.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_10.gif)

What are the headings in the data?

![babydata-04-blog-post-bottle-feedings_12.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_12.gif)

![babydata-04-blog-post-bottle-feedings_13.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_13.gif)

![babydata-04-blog-post-bottle-feedings_14.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_14.gif)

![babydata-04-blog-post-bottle-feedings_15.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_15.gif)

There are several types of activities we\[CloseCurlyQuote]ve been logging:

![babydata-04-blog-post-bottle-feedings_17.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_17.gif)

![babydata-04-blog-post-bottle-feedings_18.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_18.gif)

Right now I\[CloseCurlyQuote]m just interested in the \[OpenCurlyDoubleQuote]Bottle\[CloseCurlyDoubleQuote] activity, so I\[CloseCurlyQuote]ll filter for those entries:

![babydata-04-blog-post-bottle-feedings_20.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_20.gif)

![babydata-04-blog-post-bottle-feedings_21.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_21.gif)

![babydata-04-blog-post-bottle-feedings_22.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_22.gif)

![babydata-04-blog-post-bottle-feedings_23.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_23.gif)

It\[CloseCurlyQuote]s easier to see the structure of the data if I transpose it and view just a few entries:

![babydata-04-blog-post-bottle-feedings_25.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_25.gif)

![babydata-04-blog-post-bottle-feedings_26.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_26.gif)

The fields I\[CloseCurlyQuote]m interested in are the date/time of the feeding, and how much Toby ate. So I\[CloseCurlyQuote]ll filter just those fields:

![babydata-04-blog-post-bottle-feedings_28.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_28.gif)

![babydata-04-blog-post-bottle-feedings_29.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_29.gif)

![babydata-04-blog-post-bottle-feedings_30.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_30.gif)

![babydata-04-blog-post-bottle-feedings_31.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_31.gif)

(There\[CloseCurlyQuote]s a character encoding issue evident in the \[OpenCurlyDoubleQuote]Date and Time\[CloseCurlyDoubleQuote] field, which I\[CloseCurlyQuote]ll ignore for now as long as it isn\[CloseCurlyQuote]t obviously effecting the data values.)

The data is in reverse-chronological order, and the \[OpenCurlyDoubleQuote]Quantity\[CloseCurlyDoubleQuote] field is in ounces.

In order to start analyzing this data, I need to parse the date field into a canonical format:

![babydata-04-blog-post-bottle-feedings_35.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_35.gif)

![babydata-04-blog-post-bottle-feedings_36.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_36.gif)

The quantity field has been parsed into numbers by the CSV importer:

![babydata-04-blog-post-bottle-feedings_38.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_38.gif)

![babydata-04-blog-post-bottle-feedings_39.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_39.gif)

![babydata-04-blog-post-bottle-feedings_40.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_40.gif)

![babydata-04-blog-post-bottle-feedings_41.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_41.gif)

Haha ... we have been strangely specific about logging how much Toby\[CloseCurlyQuote]s eaten, down to the 0.05 ounce??? I doubt we\[CloseCurlyQuote]ve ever been able to discern 0.1 ounces from 0.15 ounces ;) We can maybe distinguish between 0.1 and 0.2 ounces? Anyway, I\[CloseCurlyQuote]ll take the precision with a grain of salt :)

![babydata-04-blog-post-bottle-feedings_43.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_43.gif)

![babydata-04-blog-post-bottle-feedings_44.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_44.gif)

Okay so I\[CloseCurlyQuote]m ready to parse the bottle feedings data:

![babydata-04-blog-post-bottle-feedings_46.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_46.gif)

![babydata-04-blog-post-bottle-feedings_47.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_47.gif)

![babydata-04-blog-post-bottle-feedings_48.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_48.gif)

Now the fun begins. The first thing I\[CloseCurlyQuote]d like to see is the bottle quantity as a function of time:

![babydata-04-blog-post-bottle-feedings_50.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_50.gif)

![babydata-04-blog-post-bottle-feedings_51.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_51.gif)

There\[CloseCurlyQuote]s a general trend towards larger bottle amounts per feeding as Toby has gotten older. That\[CloseCurlyQuote]s exactly what I expected, since as Toby has grown he\[CloseCurlyQuote]s been able to eat more and more in a sitting.

After Toby was about 6 weeks old, we started putting his feedings onto a schedule. The goal was to get Toby to the point that he could sleep through the night without waking up to eat. In order to do that, we followed a program that recommended a feeding schedule of eating every 4 hours during the day, and gradually decreasing the amount he ate in his night feedings. The idea is that the baby gets more and more of his daily calories during the day, and less and less during the night, until he no longer needs to wake up at night to eat.

![babydata-04-blog-post-bottle-feedings_55.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_55.gif)

![babydata-04-blog-post-bottle-feedings_56.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_56.gif)

This shows really clearly the emergence of a feeding schedule for Toby. When Toby was first born, there was no schedule! He ate when he was hungry, which was every few hours, including in the middle of the night. But after a couple of months (around June), we started organizing his feedings into bands. He would eat when he woke up in the morning around 6 AM, then every 4 hours until he went to bed for the night around 6 PM.

Then around the middle of July, Toby stopped waking up at night to eat! Yay!!!!! We can sleep!!!!!

This diurnal plot is showing only the date and time of each feeding, but is still missing the amount he ate in each instance. I can modify the plot to show this by making the size of the point proportional to the amount he ate:

![babydata-04-blog-post-bottle-feedings_60.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_60.gif)

![babydata-04-blog-post-bottle-feedings_61.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_61.gif)

![babydata-04-blog-post-bottle-feedings_62.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_62.gif)

![babydata-04-blog-post-bottle-feedings_63.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_63.gif)

I love this plot! It shows a clear progression from little 1-2 oz meals at random times of the day, to larger 8 oz meals at consistent times of the day, about 4 hours apart. And can you imagine our relief when that little meal around 2 AM went away!? We could finally sleep through the night!

Toby sleeps like a champ now. He goes to bed around 7 PM and wakes up around 6 or 7 AM, giving us a blissful 11-12 hours to have dinner, catch up on our day, and get a full night\[CloseCurlyQuote]s sleep.

![babydata-04-blog-post-bottle-feedings_66.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_66.gif)

![babydata-04-blog-post-bottle-feedings_67.gif](../../../assets/2017/08/22/babydata-04-blog-post-bottle-feedings-600px/babydata-04-blog-post-bottle-feedings_67.gif)

