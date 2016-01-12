---
layout: post
title: Errata #1
desc: On January 6, I gave some advice that has turned out to be extremely bad. It turns out that anti-virus software may even expose users to even more basic attacks than using a machine without anti-virus.
---

On January 6, in an article titled, "How to protect yourself from basic cyber attacks", I wrote:

> _Anything else you add in (keeping your computer properly updated, running anti-virus software, or running a firewall) will improve things even further, but if you do nothing else, do those two things._

It turns out that running anti-virus software may be particularly bad advice. Today, CSO Online published an article called [Antivirus software could make your company more vulnerable](http://www.csoonline.com/article/3020459/security/antivirus-software-could-make-your-company-more-vulnerable.html). In this article, they demonstrated that some major anti-virus products contain vulnerabilities that could let criminals run their own code on your computer.

As if by clockwork, a few days ago, a researcher named [Tavis Ormandy posted an issue that could let an attacker execute code on any system that runs TrendMicro's antivirus product](https://code.google.com/p/google-security-research/issues/detail?id=693). These sorts of bugs are scary because for years, the dominant security advice has been:

1. Keep automatic updates turned on.
2. Run antivirus software.
3. Stay off of sketchy websites.
4. Use strong passwords.

At this point, with the rise in malvertising and vulnerabilities in anti-virus software, I can argue that #2 and #3 are totally wrong. #1 is a good idea though it doesn't particularly help you if you run a highly vulnerable piece of software. #4 is helpful...but only if you use a unique strong password on each different web service that you use. Otherwise, if one poorly secured database leaks, every service you use is vulnerable.

I worry that there are a whole lot of people out there who have been lulled into a false sense of security. Believing that you are secure when you are highly vulnerable is significantly more dangerous than just being highly vulnerable.
