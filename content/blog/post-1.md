---
title: "How code falls behind the product"
date: 2021-02-01T10:07:47+06:00
draft: true
image: "/images/ufo-3105954_640.jpg"

# meta description
description: "this is meta description"
# taxonomies
tags:
  - "New"

# post type
type: "blog"
---

### TL;DR
- Code is always behind the product;
- The more product model differs from code model, the more the delay;
- One way to deal with it is to design for flexibility;
- Second way is Ubiquitous Language that unites product and code models.

I read a blogpost from a product manager's perspective on why software projects are delayed. Among other reasons, he mentioned "weak architecture" - basically, "bad developers" create "weak architecture" which is fragile and requires a lot of time to maintain and modify. On the other hand, if you ask developers why projects are delayed, they will tell you that "bad managers" create "weak specifications", insufficient or changing at the late moment.

### Why so slow
Here is how I see the situation, from the outside. The idea of the product drives the project; code implements the idea. The first reason for code being behind is that today we implement the requirements of tomorrow. The code is eventually consistent with the product description. 

The second reason is that the code has to deal with hardware. There are network latency, disk latency, memory and storage limitations. A simple idea ("users can update their Twitter feed") leads to heavy implications on the development side. Changing the direction of the code will always be slower than changing the idea.

### A rocket following a flying saucer

To cope with the slowness developers are trying to do prepare the ground work. With every software design decision developers make some changes easier and other changes harder. Ii is like a rocket getting a propelling momentum - it moves forward faster, but it is hard to turn around.

In such situations, the leading Agile development solution is to design for flexibility. You make your rocket go slower, but it has turning engines all over it. Then you can quickly change the direction and be agile.

Another useful thing is the Ubiquitous Language described in the DDD book. Ubiquitous Language is a common language shared between developers and product managers. Using the same terms and the same mental models, both parties form a common understanding of the system and its needs. It makes steering a bit more predictable, and it shifts the focus from fighting each other to fighting the situation together. Shortly speaking, it is all about having a dialog, a two-way conversation, instead of a one-way specification-to-implementation flow.