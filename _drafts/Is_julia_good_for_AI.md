---
title: Is Julia Good for AI?
layout: default
tags:
   - julia
---


It seems like one of the most common questions asked of Julia: "Is Julia good for AI?".
I'm not sure why it is asked so often.
Cynically, I think it is asked by people who are both new to the language and new to the field.
The question can't be readily answered without first defining AI.


AI is notoriously hard to define:
I'll quote Wikipedia's article on the AI Effect:

>The AI effect occurs when onlookers discount the behavior of an artificial intelligence program by arguing that it is not real intelligence.
>Author Pamela McCorduck writes: "It's part of the history of the field of artificial intelligence that every time somebody figured out how to make a computer do something—play good checkers, solve simple but relatively informal problems—there was chorus of critics to say, 'that's not thinking'." AI researcher Rodney Brooks complains "Every time we figure out a piece of it, it stops being magical; we say, 'Oh, that's just a computation.'"

However, that is a question of the lay-persons definition of AI.
Even the definitions of people in the field make AI a broad area.

ACM defines both AI and Machine Learning (ML) as subfields of [Computational Methodology](http://dl.acm.org/ccs/ccs.cfm?id=10010147). Most, but not all, things people call AI are from within Computational Methodology.
For example, many would consider biologically inspired systems like Evolutionary Algorithms, and Swarm algorithms to also be related to AI (They are under Mathematics of computing →  Mathematical analysis →  Mathematical optimization).
As well consider, Information Retieval to related also -- particularly since it in many ways includes the tech behind Digital Assistants like Siri etc (Information systems →  Information retrieval).
Most often today, people casually saying AI actually mean Machine Learning; in particular Deep Learning with Neural Networks.


I think it is useful to distinguish between AI and ML.
They are not the same thing; but are related.
AI is giving the apearence of intelligence -- doing things that we normally think only a person could do.
Machine learning is to have the computer in some sense learn to solve a problem from data, rather than having an explict algorithm for solving that problem written by the programmer.
In general ML is used in the implementation of AI; but it is not AI itself.

Some would say that learning is something we we would normally think only a person could do.
Thus it could be argued that ML is infact AI.
This is getting down into semantics; ML is definately in the broader class of AI, but not normally in the narrower case of doing things we normally think humans are the only ones who can do.
Most of the recent deep learning excitement is over offline, supervised methods.
These are not very human at all.
As compaired to Active Learning, Oneshot Learning, Reinforncement learning and several other ML techniques which can be argued to be more "human".
In general though I will discuss ML as distinct for the classical focus of AI.

No taxonomy or set of definitions is perfect.
Remember Diogenes' plucked checken "Behold, a man."
For informative purposes though, I am going to go though various fields using the ACM taxonomy,
and talk about how good (or otherwise) julia is for them.