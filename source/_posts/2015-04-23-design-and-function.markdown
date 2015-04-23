---
layout: post
title: "Design and Function"
date: 2015-04-23 12:41:39 -0500
comments: true
categories: design, octopress, huawei, ruby, firewalls, rake
---

##Mistakes in Design

So, I've been looking for an android wearable recently, and I have
come across the Huawei Watch. It hasn't yet been released,
unfortunately, but it looks like it is going to rival, and perhaps
even exceed the Apple Watch when it is finally released. I was
interested in maybe getting the Moto 360 or the LG Watch, but I
dislike the little flat tire design on the Moto and the square design
of the LG. The Huawei's traditional watch design looks really
fantastic, and indeed, I really enjoy it. I much prefer it to some
other watches.

But, there is an issue with Huawei's design. Not so much in the watch,
which again is fantastic, but in the design for their
[website](consumer.huawei.com/minisite/worldwide/huawei-watch/). It
looks nice enough, a pleasant theme that works well, not too many
images beyond the massive info wall, and everything looks easily
navigable. That is, until you try to scroll down to read more
information. Now, I don't know about you, but I prefer to scroll with
my mouse. Sure, I can use the keyboard, but I like keeping my hands
ready to type as opposed to over by the arrow keys. When you try to
scroll down with a scroll wheel on Huawei's site, like, you know,
normal human beings generally do, it treats each click of the wheel as
going down one "frame" in the infographic. This is absolutely awful,
and completely unlike anything else on the web. It's infuriating,
actually. Like, who could have possibly thought that would have been a
good idea?

##Complete Segue into the Project I Am Now Working On

First things first: screw the everloving shit out of corporate
firewalls. They make everything stupid difficult to deal
with. Anyways, dealing with a corporate firewall on Windows actually
isn't too bad for most things - for instance, to fix like everything
on a Windows system you have to figure out what your proxy server is,
and then you can throw that info into the System Environment variables
on your system by making a new variable: `HTTP_PROXY` with the value
being proxy.address:port. The problem is that this doesn't fix every
problem. Sure, you can use git now, and gem, and all the other super
useful commands, but not every rake command is going to work well.

Right now, we are building tests for our database. Now, normally
everything should work fine - we're using FFaker and Factory Girl to
generate data for RSpec test cases. Unfortunately, when I try to run
`rake test`, things get wonky. Specifically, it can't figure out how
to setup a local server (or something) and run the tests there. Oh
well. I guess one day I'll figure it out, and what's more, TravisCI
runs the tests, so everything at the very least seems to be working.

Man this blog is random. Eh, I'll get better at this in time, just
like I will at Ruby on Rails!!
