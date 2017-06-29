---
layout: post
title: Problems with Test Driven Development
desc: TDD has never felt right to me and this article represents my best attempt at explaining why.
---
This thought isn't fully formed, so this article will be short...both in content and detail. However, I was hacking on an open source project late last night, ran my tests, saw a whole mess of fucking red lights, and the TDD light went on in my head.

As a developer, I have some incredible skills. I'd argue that I'm unbelievably good at context switching between front and back-end development. I am exceptional at user/developer experience, mostly because I'm good at talking to people and getting them to tell me how they really feel. This skill leads me to build intuitive interfaces (whether physical, or application level) almost without thinking. And, I think I'm good at empowering my users (whether technical or not) to teach me how to make their experience better.

However, I also have some incredible weaknesses. One of them is that I'm horrible at design on the fly. I am significantly more productive if I can spend an hour on design up front and then build an entire application around that design.

When I engage in test driven development, I always feel like my code and the tests end up too strongly coupled. Consequently, if I change code, I often have to change tests to match. Then, I end up in the usual TDD quandary. Namely, do I want my tests to catch bugs, or do I just want them to pass?

So, last night, I got to thinking about the test driven development addicts that I know and have worked with. Without exception, every single one is significantly better at refactoring than I am. They are particularly good at separating concerns and avoiding highly coupled code. Since I am not an expert at design and refactoring on the fly, when I use TDD, I often end up writing significantly messier code than I would have written if I didn't have these damned unit tests to turn green.

Consequently, for my workflow, it makes more sense to write integration tests as part of my continuous integration flow. Not only do I end up with the accuracy and stability that TDD is supposed to provide, but I ship code faster and end up with a better designed, more robust application.
