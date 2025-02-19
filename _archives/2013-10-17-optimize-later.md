---
title: "Optimize Later"
date: 2013-10-17
categories:
  - Archive
tags:
  - bits
  - optimization
  - performance
  - startups
  - best-practices
---

One of Larry Wall's [three great virtues of a programmer](http://threevirtues.com/) is laziness. While I generally don't confer that laziness is a desirable attribute, when it comes to building early-stage startup software, it could not be more valuable. Laziness allows you to provide business value now, and defer performance for later. When I say performance, I mean software, business and team performance, but I primarily mean software performance. Deliver early, deliver often.

Though I've never worked at such establishments, I can imagine there are places where it's unacceptable to deliver under-performing software. There's plenty of cases where performance needs to be a primary concern, including banking, embedded systems and mathematical software. Web applications, however, do not fall under this umbrella. What's difficult is to know when performance becomes unacceptable, but that's the point. Deferring optimization allows you to measure the key facets that need attention. During the early stages, it's much more crucial to measure than to optimize.

Now, what I'm saying should not be conflated with inadmissibly slow performance. You need to draw the line somewhere. Knowingly shipping software that will affect the perception of speed should be avoided at all costs, but the optimizations that might increase revenue by a fraction of a percent can wait for a rainy day. It's the difference between fixing an N+1 query and rewriting to take advantage of tail recursion. With experience, I think performant code can be written during the first iteration; the more you optimize, the more likely you are to avoid pitfalls. So, generally I take the approach of: ship early, optimize later, learn, rinse, repeat.