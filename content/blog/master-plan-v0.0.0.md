---
title: "Master Plan v0.0.0"
date: 2018-03-18T15:21:17-05:00
description: 'wat'
draft: true
---

**note: this is still in draft/writing. Just getting it written incrementally when I can to get it out!**

I think aquaponic technology has the potential to radically change the way everyone on earth lives for the better. I want to plumb the depths of it's potential and make that freely available for every person on earth.

## Articulate Problems, then Solutions

Starting with an articulation of the problem is better than starting with a possible implementation/solution to that problem. The problem will not change over time. The implementation should.

What would such a worldwide system look like? How might it start being built?

When you could do anything, the best way to adapt circumstances towards movement are through constraints. I like the term "NFRs" (non-functional requirements) to represent these. They're not directly the functional parts of the system that are built, but prerequisites in place on anything that _is_ built which are required for the system to successfully operate. In other settings, these could be things like performance, reliability, maintainability. However, in this problem space, these take a different form.

Here are some of the constraints:

* Work anywhere on earth
* Accessible to anyone
* No proprietary prerequisite physical parts/software needed (everything should be able to plug in)
* Have built-in means to incentivize people's usage of good actors
  * Responsible iot companies (secure sensors)
  * Sustainable sourcing of other parts
* Maintain optionality wherever possible

## Data Flow

The place my mind naturally starts here is identifying the places and circumstances in which this will be used. If you identify and build for the extremes, the middle will take care of itself. The lifeblood of software is data. Tracing the data flow, and designing it to maintain the highest degree of simplicity at the start is a good place as any to begin.

No matter what requirements exist at what levels, focusing on data in ways that likely won't change is a good use of time.

**Aside**: People often conflate _ease/familiarity_ with _simplicity_. When humans encounter something new, they automatically compare it to what they already know. It's quite easy for people to look at a thing, find it far from what they know, and declare it complicated. They can see a complex thing, close to what they're already familiar with, and declare it simple. However, especially or in domains with lots of up-front ignorance (meaning unknown or intrinsically complicated), the more familiar of the two choices could be the worse one.

Ease is how closely a thing relates to existing structures in your mind. Simplicity doesn't describe a property that's there, simplicity is a negatively-produced property that emerges through lack. Simplicity is the lack of _unnecessary_ complexity.

Here is a basic conception of what such a system might look like, with basic considerations jotted down:

![Example image](/img/0.0.0/data-flow.jpg)

This has a couple core properties:

1. Each setup is treated as it's own remote 'node'
2. The flow of information to/from nodes to data consumption centers can happen via intermediary devices
3. Consumption centers aggregate data across lots of different setups.
4. Setup owners can direct and control what consumption centers get their data
5. Setup owners can direct and control what consumption centers they receive updated plans/recipes from

Obviously, I need a better word for "consumption centers," but they're the place where data is collected, analyzed, and local discoveries are exploited and turned into global improvements.

extra line for deploy testing