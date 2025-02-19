---
title: "Avoiding Technical Debt"
date: 2014-05-05
categories:
  - Archive
tags:
  - bits
  - technical-debt
  - culture
  - maintenance
  - project-management
  - code-quality
  - pair-programming
---

[A Culture of Credit](/archives/2014-02-22-a-culture-of-credit/)

There's a way out. It boils down to recognizing the signals. What's most difficult is the elusive nature of technical debt. It's hard to pinpoint. Stories take longer than usual and we begin to wonder, "what went wrong?" If you're asking yourself this question, you've got a lot of work on your hands. Through a combination of social and empirical approaches to measuring, we can form a grasp on how much debt is being introduced in real time. We can approach debt mitigation in a holistic manner, through technical and non-technical avenues.

Static analysis tools are great, but entirely objective and relatively unintelligent. Code Climate will elucidate potential code smells, which then requires human intervention to determine the implications. Test are an immediate form of feedback. Usually, a smelly test translates to tightly coupled components, which is often the root cause of decreasing velocity. The presence of existing code is what makes large projects unwieldy and the necessity to integrate with it causes slowness. If we listen to our tests, we can likely mitigate most of our technical debt.

One problem: not everyone listens to their tests to the extent needed to be debt-free. Software teams are comprised of varying skill sets, personalities, ideologies and experiences. This is where the social aspect of managing technical debt unfolds. If a team is built from two individuals who (unintentionally) increase the amount of debt owed, this team is in need of at least one individual who will pay it down in tandem. Better, pair developers who have varying, but complementary styles. For each individual who's contributions tend to increase debt, consider pairing them with someone who values and doesn't mind paying down debt. Such a pair can immediately benefit the entire team, as discussions of debt, style and value will ensue regularly.