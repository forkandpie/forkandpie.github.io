---
title: “Could you tell me, what is OOP?”
date: 2018-07-25T12:00:00+01:00
draft: false
image: "/images/whatisoop1.png"

# meta description
description: ""
# taxonomies
tags:
  - "phylosophy, technology"

# post type
type: "blog"
---
> — So, what is OOP?
> 
> — It’s a software development paradigm that includes three main principles: inheritance, encapsulation and polymorphism. The first one is _blah-blah-blah_, the second one is _blah-blah_, and the third one is _blah_.

### Dead knowledge, alive knowledge
Multiple times I was asked this question at job interviews, and I asked it myself. I even remember that learning it by heart from the first chapter of “Design Patterns in Actionscript 3”. At the start of my career I saw that every job opening had “knowledge of OOP principles” in the requirements, so I decided to learn it by heart. I guess, the question is convenient as a litmus test, it’s like the most basic theoretical knowledge. I always answered it by the book.

The sad thing is that is was actually a dead knowledge — I couldn’t apply the definition of OOP or any of the principles to my daily activity. Also I never really liked dry academic language 
— I would recommend, for example, O’Reilly’s Head-First book on 
Design Patterns over Gang of Four’s one.

But now I’m armed with a much better explanation of OOP (it’s from “The art of destroying software” by Greg Young), and it’s brilliant in so many ways:

> OOP is about small computers inside bigger computers, that communicate with messages.

### Basic OOP principles in computer metaphor
The metaphor of a computer as a unit fits OOP perfectly :
* We all know that computers usually come packed (encapsulated) in metallic boxes with several inputs and outputs that define computer’s interface. The easiest way to interact with a computer is through this interface — with keyboard, mouse, display or speaker.
* Computers communicate with each other via network with messages. Messages can carry any kind of information — text, sound, cat photos, youtube videos (possibly about cats). A computer can pack the information using special format and send out through network interface — even if no one listens to it. And then any other device with a proper interface — computer, or smartphone, or some IoT device — can react to this message. Polymorphism.
* My laptop didn’t just appear from nothing, it’s a result of many iterations and incremental improvements of hardware. Computers can inherit the properties of each other.
* As a bonus — I know that my laptop consists of several parts that are nicely composed in a plastic case. It’s easier and more convenient to upgrade just hard drive or RAM module instead of the whole laptop. This is an example of preferring composition over inheritance.

### More OOP details in the computer metaphor
1. OOP is not opposed to FP
OOP is usually explained to students via real-world objects — like a car and engine, or a dog and its barking functionality. One of the flaws is that statefulness is assumed — object always has “a set of properties and methods”. Unfortunately, I believe it’s a reason why I often see discussions where OOP is opposed to functional programming.
As soon as you remove the state out of definition — there is no conflict between FP and OOP anymore. A computer can accept a message, do some transformation and send it further — not saving the message, but keeping properties of inheritance, encapsulation and polymorphism.
2. Single responsibility is easier to assume
The computer metaphor makes it easier to impose the single responsibility principle. It’s more natural to ask yourself “what single thing this computer should do” than “what single thing this dog should do”. You have to train a dog, and it can still chew your shoes, bark at the mailman and destroy the newspaper. A computer does what you program it to do.
3. Decoupling comes into play
Communicating with messages stresses the importance of decoupling. A computer doesn’t know if another one exists. A computer only has inputs and outputs, and it can give a signal that it did something. The idea is to shift from imperative to reactive flow— it’s actually a part of Alan Kay’s original concept, that was lost in academic definition later.
4. Cohesiveness is a part of the picture
Okay, maybe it’s a stretch, but I see that cohesiveness also has a place in the metaphor. If we look at the inside of a computer, where each part has its own purpose — they are coupled together tightly, but we it’s a kind of coupling we want.
### Instead of conclusion
Maybe at some point we tried too hard to protect the “Science” part in “Computer Science”, that we switched to the dry academic language. But then we realized that it’s actually bad for communication, and we introduced metaphors of dogs and cars — but, alas, something was lost. A good metaphor is like a treasure. Luckily, books and articles were written, and the knowledge is still available to everyone.

I find it very interesting to dig into software development history, there are so many gems that were discovered, and lost, and discovered and lost again. I believe that the path to better development is not through creating and learning new languages and frameworks. It’s through learning and groking timeless laws and principles of development.