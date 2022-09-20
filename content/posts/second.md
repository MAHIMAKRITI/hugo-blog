---
title: "Youtube stats analysis | Using the Youtube API"
date: 2022-09-20T14:23:07+05:30
weight: 20
draft: false
cover:
    image: images/yt.png
    alt: 'This is about youtube views'
tags: ["data science", "python", "matplotlib"]
---
***
 ### Introduction:

What makes some Youtube video so wildly popular? What are the factors which makes the view count rise?I am personally a huge fan of 5 art YouTubers and wanted to get an indepth analysis as to what is it which makes each of these artists so wildly successful ? Is it because they post at a certain time of the day or because they use certains tags while posting or is it because their videos are too long or too short ?


**The business task**: Analyse the data collected about 5 of my favourite art-tubers using the Youtube API and see what makes them so successful or not in some cases.

The channels I will be analyzing are:
- Xabio Arts
- Pypah's Art
- Angel Ganev
- Scott Christian Sava
- Aashiyart

![alt text for screen readers](/images/YT1.JPG "Subscribers of each of the 5 channels")

**Does the number of likes and comments matter for a video to get more views?**
Firstly, I would like to check if comments and likes do correlate with how many views a video would get. In the plots below, it can be observed that the number of views and number of comments/ likes strongly correlated with each other. The number of likes seems to suggest stronger correlation than the number of comments. However, this is expected as the more people watching a video, the more likely this video will get comments and likes. To correct for this factor, we will plot these relationships again using the comments per 1000 view and likes per 1000 view ratios.
 

![alt text for screen readers](/images/YT2.JPG "Monthly rides by both categories")
Now we will take a look at the correlation if we look at the comment ratio and like ratio instead of the absolute number.

![alt text for screen readers](/images/YT3.JPG "Daily rides by both categories")

After correcting for the absolute number of views, it turns out that the correlation is much less clear. The comment-view relationship seems to completely disappear: a lot of videos have millions of views and very few comments, while some vides have very few views have better interaction. However, it is understandable that comments take more effort than views and likes, and normally comments would die off when the video gets older.

As for like-view relatioship, we can still see some positive correlation between views and like ratio (though very subtle), which means that the more views a video has, the more people would hit the like button! This seems to support the idea of social proof, which means that people tend to like better the products that are already liked by many other people.

**Does the video duration matter for views and interaction (likes/ comments)?**
As can be seen in the histogram below, most videos are between 400 to 600 seconds, which is about 6 to 10 minutes. Here I have to limit the duration to 8000 because of some really long videos (potentially streaming videos).

![alt text for screen readers](/images/YT4.JPG "Daily rides by both categories")

Does title length matter for views?
There is no clear relationship between title length and views as seen the scatterplot below, but most-viewed videos tend to have average title length of 30-60 characters.

To see code please go to my [github](https://github.com/MAHIMAKRITI/youtube_artits_EDA)

***