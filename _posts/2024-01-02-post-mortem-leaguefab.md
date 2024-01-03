---
layout: post
title: "Startup Post-Mortem: LeagueFab"
date: 2024-01-02 19:35:00 -0600
tags: startups startup-post-mortem
---

![logo](/assets/leaguefab.png){: style="float:left"} LeagueFab was my first
real attempt at a startup, and one that taught me several important lessons. I
co-founded LeagueFab in 2015 with a friend who was an avid ping-pong player.

He often traveled, and lamented the fact that it was difficult to discover where
people in the areas he was visiting gathered to play games.  We envisioned an
app that would connect players to recreational sports games of any type, and
facilitate the scheduling & scoring of competitions.


### Lesson 1: Do one thing excellently

We dove in head first building. I worked on the backend API, writing it in
Python with Django and Django-REST-Framework. My co-founder focused on the
frontend, using Angular and Ionic to build interfaces for both web and mobile.

We spent time pondering the best way to model our database to account for the
quirks of different sports, and how we could handle anything under the sun
generically. Soccer has two halves. Hockey has three periods. Football has four
quarters. Baseball has nine innings. Scoring "events" are worth different
amounts in different games. Etc. etc. etc.

None of this was relevant to ping-pong. None of this would solve the original
problem of connecting people who want to play ping-pong. And it wouldn't solve
the scheduling & scoring of competitions very well either if we were going to
shoe-horn every single sport under the sun into one model.


### Lesson 2: Don't waste time

After six or seven months, we had a working "MVP" that we wanted users to start
testing. I believe we had a single-digit handful of people who we were going to
try to get to start using the tool to manage an informal ping-pong "league."

The most straightforward option would have been to point users to our web app
and use that for initial testing.

Instead, we thought we had to launch as an app in the App Store _and_ Play
Store.  As a business account. So, we went through the process of incorporating
as a Delaware C-corp, because that's what real startups do, right? And of
course we had to agree on a share ownership split and vesting schedule for our
own equity. And then we had to go get an EIN from the IRS, and then jump
through a bunch of hoops to prove to Apple that we were a "real" business.

All so that we could publish a mobile app on the stores for our five test
users.


### Lesson 3: Talk to users!

By this point, it's probably clear that we did not have any sort of organic user
adoption and we did not do much at all to drive adoption or get in front of more
prospective users.

It's awfully hard to build a product that people love if you never talk to the
people who will use your product. Even the original iPhone had room for
improvement, and I'm not Steve Jobs.


### Conclusion

After about a year, our motivation and level of effort had tapered off pretty
dramatically. We made the decision to cease work on the application and formally
wind down the company in early 2017 rather than continue to pay various
registrations and annual fees associated with the business, since we still
didn't have any clear path to revenue at that point.

I don't even know if I realized at the time that it was a path to revenue that
was missing.

In retrospect, the issues are pretty obvious. We spent all of our time writing
code and worrying about how to be a "business" but didn't do the one thing
businesses are meant to do: <strong>make money.</strong>

Around the time we wound down LeagueFab, I had another idea come up that I was
interested in pursuing.
Datascover was my
next venture, where I was able to apply some of the lessons I learned from 
working on LeagueFab.
