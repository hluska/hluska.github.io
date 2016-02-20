---
layout: post
title: My startup journey (part 1) - the startup that wasn't
desc: It has been nearly five years since I left my position at Netsecure Technologies. In that time, I have been involved in three different teams, gone through several pivots, and learned many lessons.
---

In May 2011, I left an excellent job at a local startup called Netsecure Technologies. Our flagship product (SmartSwipe) had become a huge part of my life, the team was like my family, and I had carved out a very interesting job that managed to combine writing, working with people, buildin web apps, and leading a very innovative team. Alas, my desire to publish a magazine was rekindled and I got rather obsessed with a software product that I needed to publish it. So, with one year of runway saved up, I left the SmartSwipe project behind and went out on my own.

##Startup #1 - a return to publishing##

Publishing is the most addictive thing I have ever tried. The thrill of going from an empty InDesign document to watching people walking around, reading my print magazine was unlike anything I have ever experienced. Working with writers was unbelievably rewarding, and being able to freely publish under pseudonyms was icing on the cake.

While we were publishing the Regina Streets Magazine, I got into a bit of a feud with the North American Street Newspaper Association (NASNA). That feud lead me to start working with four other rebels who believed that street papers were viable businesses and that our vendors were immensely valuable contractors. We formed our own loose little association that believed:

- Street papers cannot publish independent thought if their survival is contingent upon receiving grants and charitable donations.
- Therefore, street papers need to be strong publishing businesses built mostly upon advertising.
- Advertising required strong distribution by highly qualified and well trained vendors.
- Therefore, publishers could not charge their vendors a per copy fee.

Since we all had experience in the trenches, building our own publications, we also realized that getting your first few papers out the door was extremely difficult. Therefore, we wanted to provide our members with a set of tools that would make publishing easier. We wanted to provide a wire service so that our members could publish works that other members had previously published. We also wanted to provide a set of tools to make it easier to actually assemble magazines. These included a version control system for writers and editors to work through, and a very simple web based desktop publishing system.

In other words, we built everything that Stacey and I would have loved when we started the RSM!

Our association also struggled with the very business model behind street publishing. As publishers ourselves, we knew how much a relatively cash free society was hurting street papers and panhandling in general. Street papers operate mostly through cash. You go into a coffee shop, pay with a twenty and give the person standing outside $4.xx for a copy of the paper they are slanging. With new payment methods suddenly gaining traction, putting money into the hands of vendors was getting much more difficult. The math of selling street papers changed to the point that nearly 40% of vendor contacts were refusing to buy because they didn't have cash.

With those ideas in mind, we started hacking on a solution. We weren't really a startup, rather we were a group of publisher who wanted to work together to make publishing better for everyone. We never organized into a business, or had serious conversations about individual equity. Rather, all of our work was going to keep our association alive - it was about solving a global poverty problem, not our own personal money problems. Consequently, I hesitate to call this one an actual startup...though it may be the most productive organization I have ever been a part of.

At the time, I had just fallen in love with the idea of using Git with my own writing, but I knew that the majority of writers I knew couldn't handle its learning curve. So, I set about building a Github-like service for writers that hid all the power of Git behind icons. Two of my partners set about building a simple, template based desktop publishing solution. Their solution was amazing. Responsive design was very new, but they built up a system where you could lay out a magazine once and generate both a print ready pdf document and a web based version that would render fully in HTML, CSS and Javascript.

With the problems solved, we were still stuck on payment, so we started trying to sell our solution. That's where we ran into our first serious problem. While new publications wanted us, they couldn't afford to pay us enough to run it. And, while more established publications instantly saw the beauty of what we had put together, they had already committed to their own ways of solving the same problems. While I was validating the idea, the most common thing that I heard was, "I wish you had built this x years ago."

Fuck.

Our business model was stagnating and we got to a point where we had a very difficult choice. If we wanted to actually open our association to members, we would need some funds to actually run the applications we were built around. But, our potential members could not afford to pay membership fees. So, we had long, difficult conversations about whether we should incorporate and seek out investors, or start looking for grants from government or charitable organizations. Considering that our entire association was founded with a mandate of building strong publications that would not rely upon grants or donations to run, the idea of going out to get grants was not very palatable. That said, we were all business minded hackers, so we knew that this would be a very hard model to sell to investors.

_Hey uh, Mr. Venture Capitalist, uh, we plan to get you a 20x return by uh, solving poverty._

_Get the fuck out of my office._

In one of the more entertaining Skype calls of my entire life, my cofounders and I agreed that we would try to turn this into a business. Since my Github for writers/advertisers was finished and they were still hard at work integrating it into the web based desktop publishing tool, I was nominated to go out and start trying to find investment. In a particularly entertaining moment, one of my friends said something like, "This sounds completely insane and not even remotely possible. Greg is perfect for it."

_Cash rules everything around me, C.R.E.A.M., Get the money, dollar dollar bills y'all._ (C.R.E.A.M by the Wu-Tang Clan)

Off I went into a cold, hard world of investment where, to my incredible surprise, I actually managed to drum up some serious interest. Investors didn't like our model at all and felt that the desktop publishing tool was a total write off, but they really like the Github for writers angle. In several meetings, investors asked me if the whole team would leave the whole street paper idea behind and fully commit to Github for writers. I always said no because frankly, that idea was way too easy to copy. Git was open source - all I did was build a really simple web interface to Git and change the verbs into more writer/editor friendly variants. We would have no competitive advantage unless we looked at that product as one part of a suite of tools for publishers.

In one particularly interesting conversation, a partner with a VC firm and I sparred over whether I was actually looking for an investment or a donation. He said something like:

_Greg, publishing is completely fucked. Nobody pays for content, nobody pays for ad space, and outside of a few huge publications who would never use your product, journalism is completely fucked. Come back when the New York Times agrees to pay you._

As sometimes happens, when things look hopeless, you end up accidentally solving a really hardcore problem. I was bored at a conference and ended up finding a [OneAPI](http://www.programmableweb.com/api/gsma-oneapi-payment-0) booth. A quick implementation later and our payment problem was solved...sort of.

Code aside, there were still huge implementation challenges. The biggest was that, by the nature of street papers, our vendors often needed to get paid faster than our solution could. There were also pesky problems related to bank accounts, tax documents, and even the legal status of contractors. Ultimately, it proved nearly impossible to find a solution that could get people with no credit, no bank accounts, and no mobile devices paid quickly in a cashfree economy. But, we did come up with an easy to use solution to provide mobile payment and distribution to magazine customers. That was a victory, though a small one.
