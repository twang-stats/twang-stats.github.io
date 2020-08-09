---
layout: post
title:  "Pagination Fails, Security Fixes, and Struggling in Life"
date: 2020-08-09 03:04:19 -04:00
author: Tony
categories: Thought Processing
---

So... it is now Sunday and I, being someone with no experience in the web programming sector, still have no idea 
at all about how to add functioning blog controls. But at least I have a functioning
link at the top of the page, so better than nothing I suppose. I'm also finding myself wasting
a ton of time on things like updating kramdown for security reasons, which to most people is probably a trivial
task, but for me... well it's not proving to be common-sense or easy in any way at all.

Tangling with Ruby a bit, what I found was a chain of dependencies that needed to be resolved: kramdown 1.17 needed to 
be replaced with kramdown 2.3.0, which is understandable. What I didn't expect was just how much of a mess this would cause
and just how many dependencies and old versions of stuff I would have to update, install, and uninstall in the process. 
Even though I am (technically) now running the correct version of kramdown, I still have no idea what I did to fix things. 
What I ended up doing was uninstalling the old version of kramdown and rebuilding the website, but after overwriting the 
entire website directory, the only things that changed were a few lines in the gemfile and the gemfile.lock. 
A good reminder for what to do next time, though that certainly felt like a lot of work for not very much.

On the topic of failure and sturggling: I am not one to have ever found myself not struggling with anything at all
in my entire life. A lot of negatives in one sentence, but fitting since it's pretty reflective of my own experiences.
I have had a lot of people tell me that I'm "smart", but I don't think that's quite fitting. I think a more accurate description
of what happens again and again in my life is this:


1. I want to do something, typically an obscure/unpopular hobby
2. Nobody around me knows anything about it, so they can't help me (may also be unwilling to get involved)
3. I try to figure out what's going on, struggling every single step of the way
4. After enough struggling, I finally figure out some trick to do what I want to do and accomplish my goal
5. People see me figure stuff out and call me "smart", without seeing the struggles along the way
6. The next time I do something and actually find myself needing help on something, other people tell me things like 
"oh you're smart, you'll figure it out" and brush me off, even when they know what's going on.
7. Repeat steps 3 to 5 ...

This is a pattern that happens again and again with everything I do and have done in the past. While I am at 
this point pretty used to it, that doesn't make it any less disheartening when I ask for help and get ignored on the account 
of being smart" or whatever it is they think of me. But on the bright side, this has certainly made me someone who doesn't 
give up easily when dealing with problems. My first instinct is to simply power through as much as I can, and if it means failing 
nonstop along the way, so be it. 

Not sure if anyone is going to read this or has ever felt this way, but if you are in this position and are feeling frustrated,
you will at least have my sympathies. Take care and I hope you eventually get the support you need.