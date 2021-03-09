---
title:  "In defence of plaintext"
layout: default
---

# In defence of plaintext

**The web is a mess.** And I'm not talking about the problems with HTML, with CSS, with JavaScript, with HTTPS itself; others have complained about those standards much better than I ever could. No, today I want to talk about the way that we, as users and consumers of the web, interact with it, and how fundamentally flawed that interaction is.

Modern websites follow what I call a *prescriptivist design*. The designers of a website determine exactly how they wish a website to appear to each user. Often, a mockup will be drawn up and then implemented by teams of programmers; in fact, much of modern web development has nothing to do with the content of the website, and everything to do with the exact details of how it appears to each user. 

This approach completely neglects the original vision of the web: a place to serve hyperlinked networks of documents. By contrast, a modern website is treated almost as its own application (in some cases, [literally](https://en.wikipedia.org/wiki/Progressive_web_application)) with its own interface, its own layout, its own stylistic and content placement standards. And the result of this hodgepodge of design is a web that, while excellent for designers' Behance profiles, is radically different to the vision intended for it. The problem here lies in the lack of visual control enjoyed by the consumer: the designer is the god of their domain, and any heretical changes must be implemented by bodged-together [Tampermonkey](https://www.tampermonkey.net/) scripts and an abundance of dark mode browser extensions. Again, the goal of providing *content* is lost, while appearance reigns supreme.

Leaving philosophy aside, there are practical implications to this design-oriented paradigm. Looking at my domain, ttccourt.com, on [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/?url=ttccourt.com&tab=desktop), one notices that the entirety of the page loads within 0.4 seconds[^1]. Taking a look at a [report](https://developers.google.com/speed/pagespeed/insights/?url=theguardian.com&tab=desktop) for The Guardian, we can see the page taking over a full second to load its first block of content, and a whopping five seconds to be fully loaded (these scores may vary, but they're accurate as I'm typing this). I'm willing to bet that, no matter how poor your internet connection, my website loads snappily and smoothly for you. The Guardian's? I wouldn't count on it. CNN's [report]() is even worse. Somehow, despite containing fewer images than The Guardian, CNN scores a grand total of 14/100 on Google's PageSpeed calculator. No content is painted at all until two and a half seconds in, and the page is only done loading after almost nine seconds in total. I wouldn't want to read CNN on a dial-up connection.

