---
title: "Coding and Perfectionism"
date: 2023-10-23T22:30:00-07:00
categories:
  - post
tags:
  - coding
---

When is software perfect? Never.

Is "Hello world" perfect? Maybe, but it's so simple and not really useful. Comparing a game like osu!(lazer), this is about 1,000,000:1 if talking about lines of code. 

- Where do I put this class, method, or line?
- What do I name this?
- How do I structure this?
- Should it work like this?
- If I hack this now, would it be a problem in the future?

It’s these questions like these that halt productivity. If working on a project that’s not yours, most of these questions can be found by looking for patterns in the codebase and conforming to them. But there can be firsts and no precedent. Maybe you want to annoy the lead of the project or find a solution yourself. The latter can make you seem like a competent contributor or get a “request changes” review / criticism for the solution.

The last question is whether you want to spend the time now or later. Say, for example, osu!(stable) is built on a couple of hacks and has survived to this day. Until the devs want to rewrite such a game. They have to support legacy systems, probably break a few really hacky parts, and add more features to keep the game interesting.

This is probably the reason why I have at least 10+ branches with changes that are not upstream. Most required a little hack or a hack that required a comment. I opened some PRs with such hacks and seemingly got merged. But when is it gonna be properly supported in the framework? When someone implements it I guess.
