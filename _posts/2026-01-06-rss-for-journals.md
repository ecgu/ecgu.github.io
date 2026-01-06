---
layout: post
title: Using RSS Feeds for Anthropology Journals (And Where to Find Them)
date: 2026-01-05 16:32:00
description: What RSS feeds are, how to set them up to follow your favorite academic journals, and a rant about accessibility
tags: academia anthropology howto rss
categories: academia
---

#### What is RSS and why use it?
If you're like me and don't like notifications for new journal publications flooding your email, I reccomend looking into an RSS feed. RSS, or Really Simple Syndication, is a way to keep up with updates on websites of your choice through one standardized format. It's quick to learn, easy to set up, and plus, it's free! RSS feeds have been around for a long time, and it's what most apps use to update episodes for podcasts.

Unfortunately, the problem is that RSS feeds are not great for monetization, since it means you can access a website's content without directly interacting with it; Facebook removed RSS feeds in 2011, Google shut down their RSS service, Google Reader, in 2013, and Elon Musk removed it after he bought Twitter. For the websites of acaemic journals, they can make RSS feeds very difficult to find if they haven't removed them outright. This is strange to me, especially when so many websites for journals have the option to share articles on Facebook for some reason, and also have bots on Twitter that post article updates into the void with 0 likes. I wonder if sites intentionally want people to not use RSS feeds so make you register an account for every site or sign-up for e-mail subscriptions instead to keep better track of user information (for good reasons, of course).

However, as our internet experiences are increasingly bogged down by advertisements, sensationalist news, AI slop, and whatever else recommendation algorithms decide to push your way, RSS is becoming a [refreshingly boring alternative](https://archive.is/20200208081939/https://www.wired.com/story/rss-readers-feedly-inoreader-old-reader/#selection-659.56-912.0). On one page, I can see all the journals I am interested in, without dealing with the particularities of each website or without fear of forgetting to save a journal in my bookmarks:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/blog/feedbrosample.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    The list of journals I follow are on the left, list of new articles in the center, and a preview of the article is on the right. Pretty neat!
</div>

Of course, I can also use RSS feeds to keep up with the news, follow blogs and new book releases from publishers and more:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/blog/otherfeed.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Here I can keep up with the job board for Anthropology Careers & Employment!
</div>

I'm not alone in advocating for a return to RSS in anthropology either: see [Grant Otsuki's guide to RSS feeds for anthropology blogs](https://www.gjotsuki.net/reconstructing-the-anthro-blogosphere-with-rss/), which makes a much more eloquent case for blogs and RSS as a way to build online community for anthropology and academia without relying on sites like Twitter.

#### How to set up an RSS reader
RSS is not an app, but a way of formatting data that can be displayed in different ways. This means you get to choose how to use RSS feeds in the "feed aggregator" or "content reader" of your choice, on whatever device or browser of your choice. My personal preference is [https://nodetics.com/feedbro/](FeedBro Reader for Firefox), which is free and can be easily accessed through Firefox on my laptop (you can use it on Chrome too). It also comes with a plug-in that searches for RSS feeds on any site you're on, although it doesn't work too well for academic journal indexing sites. Other options include [NetNewsWire](https://netnewswire.com/) (iOS; free and [open-source](https://itsfoss.com/what-is-foss/)), [Feedly](https://feedly.com/) (web, Android, and iOS; requires an account and has some AI stuff), and [Inoreader](https://www.inoreader.com/) (Android and IOS; requires an account and has a free tier). Once you have one downloaded, you're ready to add feeds to it!

#### How to add feeds to an RSS reader
If you've ever seen this orange icon on a website before, that's the RSS icon! Click on it to get the link to the RSS feed. Just copy-paste the link into your reader of choice and you'll be good to go.

Some sites like Project Muse have a [neat list of RSS feeds for all the journals that they host](https://muse.jhu.edu/feeds/list_feeds?type=article):

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/blog/musefeednarrow.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Careful, collecting feeds can be like collecting books for the shelf...
</div>

For others, they might be on the side of the main page for the journal:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/blog/critrss.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

Some of them, while keeping RSS feeds in name, go through obtuse lengths to hide links to them. This includes in the University of Chicago:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/blog/chicagorss.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    I wonder why the icon is in the About section...
</div>

And Berghahn:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/blog/bergahnwhere.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Now where could it be?
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/blog/bergahnreveal.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    There it is, at the bottom of the sidebar!
</div>

There are some journals and hosting websites that disappointingly don't seem to provide any RSS feed at all, so you'll have to just follow them the old fashioned way. The wall of shames includes:
- All of Duke University Press (*Public Culture*, *Social Text*, *Boundary 2*, etc)
- All of University of California Press (although *Representations* has its own)
- *The Journal of American Ethnology*; Strangely, *Cultural Anthropology* which is also hosted by AnthroSource has an RSS feed in plain sight, but American Ethnology doesn't!

If this changes or you find their RSS feeds somewhere, feel free to email me!

You can also find compilations of RSS feeds others have already made in an OPML file format. Simply download the file and import it into your reader. My list of RSS feeds for academic journals, which revolve around anthropology, media studies, and Asian area studies is here. You can also add or delete feeds to your liking; if you make a list of your own for other disciplines or subfields, don't hesitate to share it with others! If you run into technical issues, I'm always open to meet new people, so don't be afraid to drop a message to me either! Good luck!
