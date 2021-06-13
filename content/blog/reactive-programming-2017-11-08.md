---
title: "Reactive programming, cellular communication and psychology"
date: 2017-11-08T12:00:00+01:00
draft: false
image: "/images/reactive1.png"

# meta description
description: ""
# taxonomies
tags:
  - "phylosophy, technology"

# post type
type: "blog"
---
Term Object-Oriented Programming was introduced by Alan Kay in the 60s, as he described his vision of designing complex software systems . The term and the idea were gladly accepted by the community, and the ideology spread.

Now, it’s very understandable why the community liked the idea. As humans we tend to prefer concrete objects to abstract — it’s just easier for a brain to work with something familiar, easier to grasp. So we have objects — like items in the real world, and we can describe their properties and functions, we can put objects into objects, create objects, describe interfaces. It’s like a box of toys!

But the original Alan Kay’s idea was quite different — he had a background in biology, so he came up with an analogy that was easy for him to understand, and that others missed.

He was looking for a way to combine a lot of subsystems into bigger systems (“small computers into bigger computers”), keeping each of them independent or low-coupled. In that way, every element of the system is rewritable, replaceable and easier to maintain in general. So how do cells communicate with each other? They dispatch messages in form of molecules. When a cell changes its state and wants to notify the environment, it dispatches a molecule. That molecule floats down the stream, gets caught or attached to another molecule that can accept it, so latter can react. The important thing is that molecules don’t know about each other. They are just aware of their states, the first one knows how to dispatch a message, the second one knows how to listen and react.

And that’s what we call reactive programming. The idea is to forbid one “computer” to tell others what to do. Each one should just tell about their state and whether it got changed. Also, they should be able to react to certain state changes of others. The initial idea behind the term “Object-Oriented Programming” was Reactive programming!

But I want to go even further in search for analogies, and it really gets fascinating. There is a term in modern psychology — “I-messages”. I-messages is a method of giving feedback in a non-conflict way when you put an accent on your feelings instead of blaming others. For example, “I feel neglected without your feedback” instead of “You never give feedback”. I-messages considered a useful method in conflict resolution, sharing criticism and even for self-improvement.

How cool is that? It’s basically reactive programming principle in daily communication! When there are these great analogies between software development, cellular communication and psychology — it just blows my mind. We should talk to each other more in a reactive way!

Software development is a lot about people communication. Even the code itself — it’s a message from one person to another person, we mostly write it for other team members. One of the most important properties of a “clean code” is readability. We talk with code. So who knows, maybe writing in a reactive way we not only improve our development skills but also become better persons?

#### Awesome Links
* Greg Young “The art of destroying software” — https://vimeo.com/108441214
* Dr. Alan Kay on the Meaning of “Object-Oriented Programming” — http://userpage.fu-berlin.de/~ram/pub/pub_jf47ht81Ht/doc_kay_oop_en
* Alan Kay On Messaging — http://wiki.c2.com/?AlanKayOnMessaging
* Cellular communication — https://en.wikipedia.org/wiki/Cellular_communication_(biology)#Three_stages_of_cell_communication
* I-messages — https://en.wikipedia.org/wiki/I-message
* Microservice Development Mentality — https://medium.com/@lee.sylvester/microservice-development-mentality-7c3661fdff2c