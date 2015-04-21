---
layout: post
title: "Privilege and SASS"
date: 2015-04-21 08:50:42 -0500
comments: true
categories: [Coding, SASS, equality]
---

### Codecamp

This is my first experiment in blogging, and a lot of things have changed recently. First and
formost, my confidence regarding coding has increased! I realize that I'm not alone in where I am
(as silly as that sounds) and that while I can't recite documentation and don't really know
terminology, I have a reasonable understanding of concepts and can, with a bit of work, apply those
concepts.

This past weekend, among other things, I ended up going to a developer's conference with
my friend. While most of the conference was informative and fun, there were some aspects that
neither of us enjoyed. The first talk we went to was supposed to be a short lecture about software
development using strategy games as an analogy. We both like strategy games, and we both like
software development, so we decided to go. Things started off innocently enough - the slides weren't
great, and the lecturer seemed sort of arrogant, but then things took a hard right to privileged
asshole land.

He was discussing the concept of how software development involves limited manpower and how you want
to help train your developers to be the best they could be. This is a great idea, of course - you
always want to help your employees become better at their job, offering them the time and resources
to learn more about their craft. But he didn't mean it quite like that. The exact point where things
turned bad started like this:

> So you want to tell your recruiter that you only want A developers, because you
  only want star developers. Anyone who isn't a star developer isn't worth your time and money,
  because B developers will ruin everything you do and take too long to do anything.

My friend and I turned to each other and made a face not unlike we had just eaten a
lemon. Whole. Rind and all. I asked if he realized that purchasing the top 1% of all software
developers was a little unrealistic, and my friend asked if he realized that learning is an
iterative process and that, maybe, just maybe, the people who "just get it" had different
experiences in their lives which exposed them to programming earlier and let them get further along
in the learning process than some other developers. The lecturer responded with "I have 20 years of
experience."

Oh, that's right, twenty years of coding experience totally equips you to understand the concepts
behind learning and intelligence, because as a coder you automatically know how everything in the
world works. Other people who studied human beings, like psychologists and I/O psychologists? Their
work is meaningless next to the vast, throbbing white male programmer's ~~ego~~ mind. Things never
really recovered from there, with the lecturer losing control over the conversation as a handful of
people disagreed with some of his more absurd premises and a handful agreed. All throughout, he
maintained that there are some people who "just get it," because psychology is obviously wrong. His
views on the hiring process were equally unconscionable, but then, what can you do?

Fortunately, the entire rest of the conference was fantastic.

#### SASS and Bourbon

There was a wonderful talk about SASS (Syntactically Awesome StyleSheets) which gave a brief
overview of what SASS is (tl;dr: if fixes all of CSS's problems - allows you to nest styles and use
variables). But the meat of the talk was about [Bourbon](https://bourbon.io), a mixin library for
SASS. It essentially creates variables and methods that you can use with SASS out of the box, making
it much easier and faster to style you website. But that's not all - Bourbon also comes with a
framework, called [Bourbon served Neat](https://neat.bourbon.io). Neat is essentially a framework
designed around Bourbon, that is considerably cleaner and more efficient than other frameworks (like
Bootstrap). It has simple, semantic language, and is easy and convenient to use.

There are two more pieces to Bourbon that were talked about and demonstrated -
[Bitters](bitters.bourbon.io) and [Refills](refills.bourbon.io). These are both extremely useful -
Bitters provides a scaffolding of existing styling and CSS resources to use, and Refills provides a
community maintained library of extremely useful CSS styling elements which lets you do customize a
website basically any way you want.

What was really nice about this talk, was that the speaker was polite, funny, and charismatic - he
knew how to discuss the concepts he was presenting, and he didn't go into the talk with an arrogant
preconvceived notion about how programming should or shouldn't be.
