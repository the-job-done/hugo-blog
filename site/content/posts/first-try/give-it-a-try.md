---
title: "Give It a Try"
date: 2019-01-15T09:34:54Z
draft: false
toc: false
images:
tags: 
  - scrathpad
---

Now this is really bearbones.
I'm in a hurry to pickup the kids.


Laterz


That didn't work. Adding a title now.


I've read [this](https://nilsmagnus.github.io/post/hello-hugo/) blog post and learned how to add a new post. So I'm giving it a try :smile:


Did a bit more [reading](https://forestry.io/blog/up-and-running-with-hugo/) and figured out a few things:

 -   the ```draft``` field on new content should be set to ```false``` in order to publish it. Kind of normal.
 -   the theme comes with an example of config in ```themes/hermit/exampleSite/config.toml``` and this should be adapted to needs.
 -   the ```baseUrl``` field in config must really match. Especially for https, since the browsers will block [mixed content](https://developer.mozilla.org/en-US/docs/Web/Security/Mixed_content).


So far so good. I've managed to get the site up and running and showing something (as simple, or naïve as it is). Now on to next stage: *workflow*.


On the bottom of every page you should see the links to my social networks: twitter and linkedin. I'm looking into how to add the other ones: [mastodon](https://mastodon.social/) the [Octodon instance](https://octodon.social/@Emerix), [keybase](https://keybase.io/) and the rest. Then I learned how to use some fancy features of [Hugo](https://gohugo.io/) like [footnotes](https://gohugo.io/content-management/formats/#blackfriday-options) as you will see below. Once I get the hang of it, I will try to add these to the bottom of the page. I first need to get some nice looking SVG icons like they already have: [on github](https://github.com/Track3/hermit#social-icons).


I've setup a private repo with [GitHub](https://www.github.com) - thanks Microsoft - and copied all this existing content there. The next thing to manage is *a pipeline*. Come to think of it, I should add an explanation of all of this here, in the form of a picture -possibly even a sketch-.


And I know my current SSL Report from Qualys has a lower grade (B), I should fix the TLS cyphers at somepoint. The report can be seen [here](https://www.ssllabs.com/ssltest/analyze.html?d=emerix.ro) and I also have a screenshot of it at the time I setup the [Let’s Encrypt](https://letsencrypt.org/getting-started/) certificate. I read [Bjørn Johansen](https://bjornjohansen.no/)'s blog posts[^1][^2] to setup nginx.


I've also figured out how to format those lists. Slooowly working on it.

[^1]: [Redirect all HTTP requests to HTTPS with Nginx](https://bjornjohansen.no/redirect-to-https-with-nginx)
[^2]: [Optimizing HTTPS on Nginx](https://bjornjohansen.no/redirect-to-https-with-nginx)
