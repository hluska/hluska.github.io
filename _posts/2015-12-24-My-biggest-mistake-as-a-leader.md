---
layout: post
title: My biggest mistake as a leader (or how I fucked up a company in a long weekend)
desc: The joy of startup life is that you learn what works and what doesn't. The curse of startup life is that when something doesn't work, your company dies.
---

_I am trying to rebuild my relationship with two of the other three people involved in this startup, so I am going to be very vague about their identities until they have all read this post, approved my words and given me permission to name them. Hopefully, I will be able to add edits that will give more details._

In the height of the Edward Snowden disclosures, three friends and I decided to start a very ambitious company. News was constantly coming out of Europe about how hosting applications in the United States no longer complied with European privacy laws. This created a wonderful opportunity. Simply, where would European companies host their applications if platform as a service (PAAS) providers like Heroku or Azure were no longer in bounds?

A few emails later and I had assembled a team of people who I knew very well. One team member, an immensely talented developer, emailed her father and quickly raised a small bit of capital. Her father promised to pump more money into our company as soon as we completed a few milestones.

Our plan was to build a PAAS and headquarter it in either Uruguay or Ecuador. Our biggest problem was that it would be hard to predict our capacity and because of Moore's law, it didn't make any sense (financial or otherwise) to buy a ton of over capacity off of the start. Another problem was that once we were in South America, it would be more difficult (and prohibitively expensive) to source actual servers. So, we wanted to build a PAAS that could run on the kinds of desktop computers that we could buy at any retailer.

A PAAS is a difficult technical feat to pull off. The Heroku workflow where you do not have to configure or install any software and instead just deploy your code through Git pushes, was the industry standard. But, one of the biggest problems with this is security. You may be a wonderful, secure coder but what if I suck and our applications are deployed on the same physical box? Will security vulnerabilities in my application give attackers a surface through which to kill yours?

Because of this, our investor insisted that, as a first milestone, he wanted to be able to go to a retailer, buy a desktop computer, go home, install our software, deploy a few web apps, and pay for a security audit. If we passed the security audit, he would pump enough money into the company that we could move to South America, buy some computers, pay ourselves meager salaries, and get the business off the ground.

Sounds like a good plan, hey?

As a condition of his investment, he wanted to personally know the senior leadership. He knew me fairly well as I had dated his daughter for a time. And, he obviously knew his daughter, but he did not know the other two guys who were involved. They are two immensely talented software engineers who completed PhDs from a fairly well known school. Therefore, he imposed that I would be the chief executive and that in business matters, I would be his only contact. He feared a conflict of interest so he chose not to work on business matters with his daughter, but still insisted that she manage the engineering side of the company.

This created a very interesting power structure within our company. Essentially, our investor decided whether we lived or died. His daughter managed the technical side of the operation. She reported to me. And, our other two co-founders reported to her.

Allowing this was my greatest mistake ever and was the biggest factor in taking a billion dollars of potential and killing it in a short time. I ignored three very important things.

The first thing that I ignored was that my investor's daughter was an amazing developer, but that she had problems as a manager. When she managed my work on an open source product, if I was lucky, her feedback was "this is fucking horrible." If my mistakes offended her, she would suggest that I go on permanent disability because I wasn't smart enough to work anywhere. Or, there was the time that she suggested that I had somehow evolved from a rock.

The second thing that I ignored was the greater culture within the technology world. I am a straight, cis-gendered white man so I have never personally experienced any gender or racial harassment. But, unfortunately, women have an immense amount of difficulty within the world of technology. From outright harassment and misogyny to more systemic barriers, women have a difficult time getting the respect that they deserve.

The third thing that I ignored was the fact that our other two co-founders were both from a very patriarchal culture where men rule the roost.

I ignored these things because I believed that the titles were mere formalities and that the four of us were a team working on a problem together. This assumption killed us because I was technically the CEO. At the time, I thought that title was bullshit. We had raised enough money to incorporate, draft articles, issue some shares and buy a domain. I was 'CEO' of a company that didn't have a product and had less than $100 in the bank. Further, we were all friends who had worked on projects together, travelled together, and gotten 'I really love you man' drunk together. I thought that we were a totally flat team that had assigned two titles to raise a round of capital.

I thought wrong.

If you're going to make a mess of something, it's better to fuck it up beyond all recognition, so I made another huge mistake. While I am quite technical, the three of them were working on a problem that I couldn't even get my head around. When I read their IRC conversations, my brain hurt by the end of the third line. I simply was not qualified to help them, so I trusted them to figure shit out and devoted myself to fundraising.

And, that's when I made the biggest mistake that I have ever made in my entire career. At the time, I had something of a tradition of spending Canadian Thanksgiving in the Rocky Mountains doing some hiking and eating my body weight in bad food. Fundraising was going extremely well - I had three other investors committed to write cheques at a valuation that made me feel tingly all over. So, I checked in with my co-founders before I left and made sure everything was fine. Our CTO was great - she thought that they were making great strides. My other two co-founders were assigned to a very difficult project. I knew that they were struggling, but I wasn't qualified to help them and they told me to go. So I did.

Ooops.

My friends all have quite a bit more money than I do so I think that when I said 'camping in the Rocky Mountains' they thought that I was staying in a nice chalet somewhere with running water and fast wifi. In my case, I was staying in a camper without even the slightest hint of a cell signal. Either way, I think that they thought that I would check in. I didn't and everything went to hell.

The first sign that something was fucked was the day that I left. I got into Calgary, stopped for breakfast and checked my email. My poor little phone downloaded more than 250 emails. The first one that I read started with seven little words:

_Everything was fine but you got you (sic) period_

Fuck.

That was the high point of the whole email. It continued for another several hundred words detailing our CTO's various failures and finished with a threat to sue her and her father.

Fuck fuck.

By the time I worked through what had happened, the damage was already done and our company was dead. Our CTO replied while I was reading back through emails. She was understandably hurt and called them shitty developers and misogynists, but she included her father in the exchange so he could read the whole shebang. 

Fuck fuck fuck.

When I made it back to Regina, her father sent me the single scariest email that I have ever received. It consisted of one character:

_?_

For future reference, when very rich people with money stretching back several generations only write one character, it means that you are fucked. Even if you can solve the problem, you are fucked.

I got everyone onto Skype and we had a conversation about it.

While I was gone, everything went to hell. You see, our CTO assigned our co-founders to work on a problem that she already knew how to solve. She either wasn't very confident with her solution or she wanted to show off, so when they were struggling, she didn't provide any guidance. She claimed that she didn't provide them with guidance because she wanted to see if they could come up with a better solution. That would have been fine, but when they submitted their code, she immediately removed it from the repository, replaced it with her own solution, and closed the issue.

When I say 'immediately', I mean within minutes. It took her mere minutes to evaluate their several thousand lines of code??

Fuck fuck fuck fuck.

So, there I was in charge of a fully fucked team. Our CTO wanted to fire our other co-founders. They wanted to fire her and even threatened to write a letter to her University to accuse her of having a lack of academic integrity. I was presiding over a team that had fallen apart in a fit of outright misogyny and shitty leadership. Joy to the world. The worst part is that I really wanted to fire all three of them.

In the end, we sputtered a quiet death and went our separate ways. The other two guys wrote her University a letter (on their University's letterhead) and accused her of being dishonest, subconsciously racist, and impossible to work with. She ended up dropping out of school. And I have been nervous about co-founders ever since. In good news, her father and I have stayed friends - he emails me every few months and after I push this to github, I will email him to get his thoughts.

However, as bad as this situation was, it doubled as one of my most profound learning experiences. I learned some very important things.

1. The moment you hand out Cxx titles, you are no longer a totally flat team. I was the CEO and it was my job to lead. Instead, I worked in a totally different part of the company, completely ignored what was happening in the rest of the company, and then went camping. Camping was particularly dumb - had I checked my email on Friday, it would not have been a crisis on Monday.

2. Nepotism, thy art the enemy. Consider what I did. I dated someone for awhile. Her dad respected my courage and liked me, so when we had a chance to start a company together, he jumped to invest. But, his investment was contingent upon the two people he trusted to take on senior leadership. Had the CTO been anyone other than his daughter, we might have been able to salvage the company.

3. When you're the boss, you need to know everything. I was not qualified to participate in the conversations, but I still should have actively managed the projects. None of this would have happened had I known that the CTO gave our co-founders a tough task that she had already solved. Nor would it have happened if I had stepped in and asked her to give them some guidance.

I know that I have squandered some huge opportunities in my life, but letting this team flame out was my most profound mistake. Not only did it cost me the chance to help build a company that would change the world, it cost me some very dear friendships. I am very sorry for my mistakes and though I can't fix the past, I have definitely learned. I am a better leader today because of this experience.
