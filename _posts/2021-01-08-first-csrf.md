---
layout: post
title: My first CSRF  
subtitle: How I found my first CSRF
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/csrf.png
share-img: /assets/img/path.jpg
tags: [hacking, csrf, bugbounty]
---

I've been using Barker! Which is a platform on Bugbountyhunter.com for over a week since writing this, I was worried at first thinking I was way outta my depth and I wouldn't have 
a clue what I was looking for but as previously mentioned I have @Zseano's methodology and it has been working, I also have access to his Discord server where, if stuck of you are struggling with a bug, you can find help in there - I've not seen anyone directly say (Do this) which is great because we don't want complete walkthrough's else your just copying someone else's work. Im not shy of a walkthrough, I do use then and especially in the early days - trying to decode what on earth was on my screen was terrible but I've since been able to complete certain tasks on my own and without the need for a walkthrough. 

![CSRF POC Generator](/assets/img/csrf_gen.gif)

My first CSRF - Cross Site Request Forgery, pretty pleased with myself when I found this and it was also the day I realized how powerful Burp Suite was, If you don't know what Burp suite is here's a paragraph below. 

"Burp or Burp Suite is a set of tools used for penetration testing of web applications. It is developed by the company named Portswigger, which is also the alias of its founder Dafydd Stuttard. BurpSuite aims to be an all in one set of tools and its capabilities can be enhanced by installing add-ons that are called BApps.
It is the most popular tool among professional web app security researchers and bug bounty hunters."

It's a great tool and I wouldn't be able to bug hunt as much as I am without it, I will create other posts about bugs I have found and how I find them as I go along, It's scary how easy it is to manipulate the information going across if a website has inadequate security. 

The bugs I'm reporting in this blog are mainly from Barker! which is setup to have bugs found however its not easy and they aren't in your face or as simple as DVWA or Bwapp Bee Box.

Cross-site Request Forgery (CSRF) leverages the authentication and authorization of the victim when a fake request is being sent to the server. A CSRF vulnerability that affects privileged users, such as admins, could result in a full compromise. If successful, the victim's web browser is tricked by a malicious website into unwanted action - it sends HTTP requests to the web application as intended by the attacker. Normally, such a request would involve submitting forms present on the web application to alter data. 

To do this I used burp and CSRF POC Generator which can be found on Github, I submitted my data to the server and intercepted it with Burp, Once I have that data I load it into CSRF POC Generator and created a HTML site which has a little submit button, change the data within the HTML that you have just created > save and re-open that HTML and there you have your CSRF / HTML which can change the data for that account with one click of a button. (Submit)

It was that easy, now that was on a training platform but the principle is there - read between the lines and think about the data and where it is going and you will begin to understand what to change and what to FWD in burp. It'll all make sense. 

That's all for this CSRF post, I may revise it or if I find another CSRF I'll blog about that too but in the meantime keep hunting and let me know if you've found any bug on your hunting journey. 

There is a subscription fee for @Zseano's platform and once in he gives you access to his methodology which admittedly at first; I was reading and had absolutely no idea what I was reading, instead I decided to take each bug on one by one and work my way through his methodology rather than loading my brain with too much info. I know there is plenty more to be covered inside his book but it's best to start of on the small stuff and work up, by small stuff I mean XSS and SQL ~ If I can find them after a day then you can! 

CYA - 


