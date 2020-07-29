---
title: "Introduction to Test Driven Development (TDD)"
categories:
  - blog
tags:
  - introduction
  - test driven development
  - tdd
  - developers
  - IntelliJ
---

I recently gave a talk at the [Barcelona Java Users Group](https://www.barcelonajug.org) (yes, my beloved 🥰 Java community). Specifically was an [Introduction to Test Driven Development](https://www.barcelonajug.org/2020/06/introduction-to-test-driven-development.html) and it is based on most of the experience I have accumulated over the years practising TDD. Here you can take a look at [the recorded session](https://youtu.be/1RtYeA0cqM4)

It was a great experience and at the same time a bit stressful (but only during a few seconds 😅). Let me explain it a bit about what happened: I was giving the presentation without no problems. I started talking a bit of history around TDD. I continued with why I think it is interesting to think about, or at least to see if it could work for you or your team. There are many reasons, but I think it makes sense to emphasize that it has been proved that the software you will write applying TDD it is likely to have fewer bugs ([approximately 40% fewer defects according to some papers](https://ieeexplore.ieee.org/document/1251029)). Next, I shared how the process works and the rules we have to follow. Probably you may know the process:
1. write a test that fails,
2. write the minimum code that makes the previous test pass,
3. refactor the code

![test driven development process]({{ site.url }}{{ site.baseurl }}/assets/images/tdd.png){: .align-center}

I like to say, that it is not difficult to understand how to start with TDD, but I think it takes some time to master it properly. 

Back to the presentation, I explained some of what I consider to be good habits when using and applying TDD. Then, I followed up with the live coding part of the presentation, where I demonstrated how to apply TDD with a simple kata. Then, suddenly, [at some point, 😉](https://youtu.be/1RtYeA0cqM4?t=2399) while I was using [IntelliJ IDEA](https://www.jetbrains.com/idea/) in [Presentation Mode](https://www.jetbrains.com/help/idea/ide-viewing-modes.html) the cursor disappeared. I was writing some code, I selected an expression, I moved a line up, and magically the cursor disappeared, just like that 😅

![women on the verge of a nervous breakdown]({{ site.url }}{{ site.baseurl }}/assets/images/mujeres_al_borde_de_un_ataque_de_nervios.jpg)

I am a big fan of IntelliJ IDEA. I think it is one of the best IDEs you can use. In fact, if you are regularly building and changing code with Java, I think it is the best one (or at least one of the best) you can use. By far, it has the most powerful [options and features in terms of refactoring](https://www.jetbrains.com/help/idea/refactoring-source-code.html) your code safely (unless I know about it). Once you are used to it, you will not go back to another IDE (at least this is what happened to me a long time ago 😉). What happened was really weird and I assume that probably the _antivirus_ (yes, by corporate reasons I have to use one) or either _Zoom_ (yes we found some issues while pairing with IntelliJ) was the responsible of the problem. 

Would you like to know some funny thing? I shared this presentation 2 times at [Dynatrace](httpw://www.dynatrace.com) working in the same way, with the same software and setup, and I didn't have a problem. You know, with software there is always a possibility to have something different (a byte, a comma, etc) and things could always go wrong 🤷‍♀️ (at least in a live coding session 😅). The saying on this occasion may be, no matter how many times you can prepare a talk, I'm sure every single time you give it, it will be a bit different 🤔. But, I guess this is exactly the beauty of this art of giving presentations, isn't it? 😃

Lastly, comment that in the last part, I explained a little about what pair programming is all about so that I could finally offer participants the opportunity to write some code. Once we arrived at this moment, we separated by pairs to be able to solve some of the proposed katas. 

![homer thinking]({{ site.url }}{{ site.baseurl }}/assets/images/homer_thinking.jpg){: .align-left} Here you can check [the slides of the session](https://www.slideshare.net/icougil/introduction-to-tdd-236872321) and the [video of the session](https://www.youtube.com/watch?v=1RtYeA0cqM4). I hope you enjoy the recording, I think some people might learn some techniques or tips... or might just thinking around TDD, what we call in Spain _"que te pique el gusanillo"_ 🐛, more or less _"awaking your interest"_ 😉

PS: I know, I have to learn on how to be steady: every now and then you can hear the microphone I had hanging on my shirt rubbing (sorry about this 😅). Maybe I have to buy a better microphone or use a wireless headset to avoid this kind of problems 🤔

PS2: Please, do not hesitate to ping me or share with me in which areas or topics I should improve. Here you have [the feedback form](https://bit.ly/intro-to-tdd-feedback) I created to get all your opinions. Any feedback or suggestions are more than welcome 😃 !
