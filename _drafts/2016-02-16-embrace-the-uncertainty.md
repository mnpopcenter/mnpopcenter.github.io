---
layout: page
title: 'Embracing the Uncertainty of Software Development'
teaser: 'Thoughts on how to avoid being fooled by the false certainty of deadlines and estimates and approach our work more honestly.'
author: fran
categories: team
---

Certainty.  Human beings crave it.  Organizations full of humans crave it even more.  Software development has precious little of it.

As an IT director, I’m often asked a question about the future that requires an answer with high certainty. For example, I may be asked in December “Will the new system be launched by the end of March in time for the conference?”  And what they really mean by that is "Will all the functionality that we outlined at the start of the project be ready to go by March?" The only truly honest answer to that question is "I don't know". The reason is simple:

**Software development is an inherently unpredictable task.**

I’m guessing this statement feels right to any software developer or software team manager reading this, but it may not be intuitive to the rest of your organization. Some may want to argue about that statement, but history is full of evidence in support of it. Software development is a minefield of unknown unknowns[^1], which makes for a huge margin of error on any prediction about the state of a software system at some future date. Software projects are infamous for being [incredibly hard to accurately estimate](http://www.infoq.com/articles/software-development-effort-estimation).

And yet, as organizations we will continue to have deadlines and we still need ways to plan for the future. Deadlines are very real and come with serious consequences for the organization. Even without specific deadlines, organizations are collections of finite resources and we’d like to be planful about how we use the resources most effectively. So, at once we both need certainty and cannot provide it. Quite the dilemma!

Often, teams respond by ignoring this reality.  As part of our desire to feel like we know what is going to happen, teams sometimes go to great lengths to make long-term plans with very specific promises about when work will be done. We engage in convoluted estimate-making exercises. It’s because we want to have that certainty, and we feel good when we can look at something that seems to say “yes, we’ve got a plan in place that says we’ll be done that project by the deadline!” I'm as guilty as the next guy - I still feel compelled to put together artifacts such as a high-level annual roadmap.  And every time I sit down to do so, it’s not long before I start to feel like I’m throwing darts at a dartboard when I try to project what we might be working on in Q3 or Q4 of the year.

More often than not we learn the hard way that our great plan was really just a house of cards that collapsed under the weight of the uncertain reality of software development. And that process can be painful, emotional and relationship-straining. It’s no fun at all, and I’m sure many of us have been there. As software teams, we need to find approaches that help the organization meet its goals and execute its business plan while being based on honest communication about what we do or do not know and can or cannot predict.

I’ve been thinking a lot about this problem, how to talk about it in our organization, and most importantly, what to do about it. For inspiration, I looked at Agile. I thought that the Agile community might have something to say about the topic given that Agile is a set of software development approaches specifically designed to manage the risks associated with software development. And indeed, Ron Jeffries, one of the original signatories of the Agile Manifesto, [tackled the topic](http://ronjeffries.com/xprog/articles/jatmakingthedate/) back in 2005. But Agile still tries to embrace traditional deadlines (by that I mean deadlines that say we'll have X done by date Y) via the "velocity" concept.[^4] That feels bad to me because it's trying to use past performance as an accurate predictor of future results. The Agile community didn't have a better answer for me, and after some more research, I felt that it was a topic deserving of more exploration, so I sat down to begin work on this post.

Let’s ask a fundamental question: *Why is software development an inherently unpredictable task?*

There are a lot of correct answers to that question. One is that requirements are usually changing as we go (“feature creep”). Another reason is that software development comes with a lot of complexity not directly related to the problem at hand. For example, perhaps we end up wrestling with some limitation of the infrastructure (eg. not enough memory/network/processing/storage). A third set of reasons has to do with human factors. An effective software team results at the confluence of the right knowledge and the right team chemistry, and it’s incredibly hard to get the right team in the right place at the right time.

But I think there’s a simpler, more fundamental reason for all of this uncertainty, which is that all but the simplest of software development involves the creation of a solution for a novel problem. Sometimes there are similar systems to draw inspiration from or to repurpose, but there’s almost always an element of the truly new when doing any sort of significant software work.

With the creation of anything new, it’s impossible to know up front how long it’s going to take or which parts are going to be hard.  To know that would imply that you already know how to solve the problem, which would mean it was a solved problem, which would mean you don’t need the piece of software you’re about to write. Sometimes you may have hunches or gut feelings or educated guesses by using past projects that feel similar as models, but don’t confuse those with knowing.

*So we must accept that we don’t know everything we need to know about how to solve the problem.* [^5]

If we don't know everything about how to solve the problem, then naturally we also cannot know when we’ll be done or what the path to a solution will look like in its entirety. We cannot estimate and plan our work in the same way that a factory can estimate how long it takes to produce a quantity of widgets.  Widget making is a solved problem; creation of novel software systems is not.

This seemingly self-evident idea - that if we do not yet know how to solve the problem then we cannot know when we’ll be done - is so easily forgotten. We don’t want to believe it because the implications can make us feel powerless. So sometimes we trick ourselves into pretending we can know the unknowable. But to pretend we can do this for our software systems is dishonest - to ourselves and to our collaborators. As software builders we generally know we can make the system do X, and we know we can do something by date Y, but we most certainly do NOT know that we can do X before Y for any but the most trivial instances of X. There are so, so many ways in which even a seemingly straightforward software system build can go sideways, and it's very rarely in a way you could predict at the start.

So, if tricking ourselves into thinking that X will be done by Y is a bad way to work, then how should we work?  I’ve achieved some hard-earned clarity on this over the past few years.  In short, this is what I’ve concluded we should do: 

**We should identify the most important things and work on those things until they’re either done or no longer the most important things.**  

That's it. That's the most honest thing we can do.

Note that the statement has absolutely nothing to say about deadlines or estimated work.  That’s quite intentional. The statement makes no promises we cannot keep, but simply ensures that we’re focused on the things of most value to the organization.

Adhering to this statement leads to a beautiful outcome: if you approach your work in this way, you can guarantee that wherever you do end up achieving in any given period of time will represent the best results that were possible, even though you started out not knowing what that was. Pretty neat, eh?

Of course there are devils in the details. How do you define the most important things? What are the criteria? That's where open communication on the team, especially between the technical and business sides, is critical. "Most important" is a subjective concept, and the answer is going to depend entirely on what is going to bring the most value to the organization - which is a very local concern. Sometimes that's having as many features as possible done by a certain date. Sometimes it's having some critical set of features done no matter how long it takes (the "minimum viable product"). And of course, "most important" can and will change over time, and the team needs open, frequent conversation to be able to adjust to those changes.  

Does this mean deadlines and estimations are worthless?  No.  Deadlines and estimations are important data points to help inform the team’s decisions about what is most important to work on.  But it does mean we need to redefine our expectations of what a deadline or an estimation can do for us.

When it comes to deadlines, we need to approach them as “an important date by which we want to deliver the most value possible.” A deadline cannot be a contract or guarantee about what is to be delivered, because we do not know what the "most value possible" is yet.

Estimates are also relevant, if done correctly.  And by correctly I mean at the appropriate level of granularity.  I find it helpful to think about estimates on two very coarse-grained axes.  

Axis one is size. A scale I like to use is small, medium, large, extra large.  The team can decide what those mean; one system I often use is to think of small as “feels like an hour or less”, medium as “feels like a day or less”, large as “feels like a week or less”, and extra large for everything else. It’s important that everyone realizes these are “gut feeling guesses”, not promises or facts.

Axis two is risk: low, medium, and high.  The team will generally have a hunch about whether something feels low, medium or high risk based on how “new” or “different" it feels and how prepared the team is to deal with it.  As with the size estimate, this is just a guess, but it’s still helpful.

If you do deadlines and estimations in this way, the team can have conversations like “the big conference is only a month away and we’d like to have as long of a list of new features as we can, so lets focus on small size, low risk tasks right now.”  That’s an honest way to work - no promises, but everyone’s on the same page about what’s most important to work on right now, and knowledge of deadlines and coarse-grained estimates can contribute to that determination.  [^6]

It may sound like a scary way to work. Many people are used to working in a way that feels more certain, but by now I hope we can see that when we work in that mode we’re not actually getting any more certainty, we’re just pretending we are. In software development, the only thing we can truly control is what we choose to work on and doing the best job we can.

Pretending to have more certainty about the future than you really do breeds false confidence, broken promises, and leads to people feeling bad and teams breaking down. Chasing deadlines leads to bad outcomes like buggy code and rediscovery of [Brooks' Law](https://en.wikipedia.org/wiki/Brooks%E2%80%99_law). And all of this is likely to compound on you down the road in a way that will make you say “I wish we had just taken the time to do this right back then.”

Avoid these pitfalls and stay focused on the one thing which you can control:

*Identify the most important things and work on those things until they’re either done or no longer the most important things.*

Anything else is dishonest.

--

[^1]: "There are things we know that we know. There are known unknowns. That is to say there are things that we now know we don't know. But there are also unknown unknowns. There are things we do not know we don't know." Thank you Donald Rumsfeld.

[^2]: 

[^3]: 

[^4]: Velocity is a method of calculating a team's productivity by looking at past iterations and adding up the estimates they produced for the work the team was ultimately able to complete in each iteration. The team can then compute a velocity by averaging these historical rates of output and then estimate how long the remainder of the project will take to complete by *assuming that average velocity over the remaining iterations will be about the same.*  It's that last assumption that bothers me. 

[^5]: Isn’t this the very appeal of our work? That it’s not a rote regurgitation of the same solutions over and over, but that there is an undiscovered space that you need to work towards and uncover as you progress? It’s a big part of why we all choose to do this, I imagine.)

[^6]: I also find the broken iron triangle concept to be good scaffolding for having these sorts of "what's most important" conversations with the team. Scott Ambler has a good writeup here: http://www.ambysoft.com/essays/brokenTriangle.html