---
layout: post
title: Project Goals
date: 2024-08-10 22:50 -0400
---

Figured I would lay out what my goals and motivations are for this project.

What I am doing
 * Making an open source instrument-side SCPI implementation.
 * From a consumer perspective, it should be easy to use
 * Embedded as first-class supported platform

Why I'm doing this
 * I want to leverage my 7 years of experience in SCPI to make it the right way.
 * Resume and skill builder

My experience
 * I worked at Keysight for 7 years
 * My team created the third generation SCPI parser (ksf-scpi). I led the team for two years.
 * I was one of the SCPI domain experts

What I want to get out of this
 * Learn new technologies and tools
	* ANTLR
	* CLion, sanitizers, and static analysis
	* CI, embedded
 * Several new techniques with C++
 * Have a project that is truly "professional"

Basically, I was the leader of one flavor of SCPI in Keysight and was laid off. During my time there, my team always had more to do than time to do it. There was 30 years of cruft and bad practices. After being laid off and having a few months to reenergize, I want to leverage my experience in some way. Seven years of implementing SCPI gives me industry knowledge of an industry standard from the primary company that wrote the standard. That's pretty valuable in my opinion.

The Keysight code implemented the parsing code by hand. It was delicate and complex. I've since learned about the ANTLR project and it seems to solve almost every problem I had to deal with parsing over the seven years I worked on it. I'm so stoked to use the ANTLR library!

Near the end, I was the grumpy engineer that made stuff work, but was very unhappy about how I had to make it work. Now, no one can tell me no, so the work is going to be done my way. Refactors, tests, documentation, static analyzers, modular architecture... It's going to be pretty awesome.

I've done some interviews and it has been a pain to do coding exercises because I don't have any code to show interviewers. So this project is also for that.

Apart from using my SCPI knowledge for some kind of good in the world (although, I'm not sure how much overall good it will be considering the primary consumers will be giant corporations...), I want to create this project as a way to say, "Hey, you probably want an experienced engineer help your team integrate SCPI into your project. Hire me as a consultant/contractor."

I am a bit concerned about how when my Keysight team first started our 3rd gen SCPI parser, some of the old guard was very skeptical and cautioned us that one does not simply make SCPI work. This is going to be a huge project.