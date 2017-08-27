---
layout: post
title: How Ryanair Solved Performance Issues With the New Website
date: '2016-07-22 11:17:25'
tags:
- uxdx
- fabrizio-fortunato
- frontend
- developer
- ryanair
- cto
- ryanair-labs
- ryanair-website
---

Since launching a beta version of the new Ryanair website in October 2015, guys from Ryanair Labs department have been working hard to improve major issues with the website’s speed and performance. Although choosing Angular as a framework was a good decision to make, load time of the first launch showed there are definitely issues that should be resolved.

Fabrizio Fortunato, a Frontend Developer at Ryanair, recently shared some tips on the performance improvements and upgrade strategies they have made in the meantime. Let’s take a look at the top 3 of them:

**1) One-time Binding**

Before implementing one-time binding, ask yourself these two questions: *“Will my template data change?”*, and *“Do I want to lower my number of watchers?”* If you answered yes to both, don’t hesitate to use one-time binding. For developers, adoption is very simple, and the performance gains for apps can be huge.

**2) Lazy Loading**

A simple solution that had great impact on the performance of the Ryanair website. ​Instead of bulk loading all of the content when the page is accessed, content is loaded as the user requests it. ​ Since only a part of the website needs to be downloaded, load time can be significantly improved.

**3) Upgrade**

Having an existing Angular 1 app doesn't mean that you can’t enjoy the benefits and new features of Angular 2. Check ngUpgrade and ngForward modules and decide which of them suits you better.

Are you curious about more performance tuning techniques in Angular? Watch the full Fabrizio’s talk below

<iframe width="560" height="315" src="https://www.youtube.com/embed/Fm0lgEVZFVs" frameborder="0" allowfullscreen></iframe>