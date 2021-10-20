---
layout: post
title:  "Publix Buy One Get One (BOGO) Notification"
date:   2021-10-21 16:21:00
categories: Twitter Publix BOGO Notification Beer Wine
---

It’s that time of the week to go grocery shopping and as you are walking down the aisle you see an item you like. You grab the item but then realize that it is Buy One Get One (BOGO) so you grab another one! Who doesn’t like that feeling? You get two items you like, and you are saving money. Or maybe you don’t save money because you buy multiples of two of that item?!

Now wouldn’t you like to know when the items you like are BOGO? I developed this small python application that does just this, the Publix BOGO Notification ([Github Project][github-publix-bogo-notification]). This application only works for Publix, southeastern grocery stores, BOGO items. The Publix BOGO Notification application searches Publix’s BOGO items based on provided keywords and then posts them to Twitter.

Below is an example of the application posting when beer is BOGO. Also check out the various Twitter accounts: [PublixBOGOBeer][publix-bogo-beer] and [PublixBOGOWine][publix-bogo-wine] . Cheers!
![BOGO Twitter notification screenshot](/assets/images/2021-10-20-publix-bogo-notification-example.png)

The application can be run on a server or on AWS Lambda. The setup instructions can be found in the Github projects [readme][github-readme]. Feel free to help in the development of this application by forking, creating issues, and issuing pull requests ([Github Project][github-publix-bogo-notification]).

[github-publix-bogo-notification]: https://github.com/DFieldFL/publix-bogo-notification
[publix-bogo-beer]: https://twitter.com/PublixBOGOBeer
[publix-bogo-wine]: https://twitter.com/PublixBOGOwine
[github-readme]: https://github.com/DFieldFL/publix-bogo-notification/blob/main/README.md
