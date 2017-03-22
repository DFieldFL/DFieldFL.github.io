---
layout: post
title:  "Slack Beer Bot"
date:   2017-03-21 22:27:00
categories: Slack Beer Bot Search Untappd BreweryDB
---

There's nothing like going to a local micro brew or hitting up a bar where craft beers are available. Having the ability to try a variant of beers and sharing my experiences with my friends is fun and exciting. When I find a beer that I like I usually send a text with a picture of the bottle. This may require getting the right angle, setting the flash and possibly typing the name of the brewery and beer out. This becomes tedious to do every time you find a beer you like.

A lot of times I like to share my experiences with some local tech groups I am apart of, which primarily use Slack for communication. So I sought out a way to easily share beers over Slack. At the time, I unfortunately did not find any Slack integrations that allowed a user to search for beers and then display them to a channel. So I ended up developing one.

Today I present to you the Slack Beer Bot ([Github Project][github-slack-beer-bot])! This bot was developed to integrate with the [Untappd][untappd] (preferred) or [Brewery DB][brewerydb] APIs so that a user can search for beers and display the beer with an image, description and link to the integration of your choice (Untappd or BreweryDB).

Directions for setting up the Slack Beer Bot are on the [GitHub][github-slack-beer-bot] README. Basically you will have to setup a few Slack slash commands to point to a node server that has API tokens for the integration of choice (Untappd or BreweryDB) and Slack. Once up and running commands like `/beer search Yuengling` and `/beer display Yuengling` are available to every user. Below are examples of displays for a given command.

`/beer search Yuengling`
{% highlight md %}
Traditional Lager - Yuengling Brewery id: 16649
Light Lager - Yuengling Brewery id: 3813
Black & Tan - Yuengling Brewery id: 3815
Oktoberfest - Yuengling Brewery id: 77287
Bock Beer - Yuengling Brewery id: 5249
{% endhighlight %}

`/beer display 5249` or `/beer display Yuengling Bock`
![Beer display screenshot](/assets/images/slack-beer-bot-display-example.png)

Please feel free to try out the Beer Bot on your own Slack and contribute any improvements back to [GitHub][github-slack-beer-bot]. Enjoy!

[untappd]: https://untappd.com/
[brewerydb]: http://www.brewerydb.com
[github-slack-beer-bot]: https://github.com/DFieldFL/slack-beer-search-bot


