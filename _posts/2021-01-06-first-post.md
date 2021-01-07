---
layout: post
title: BugBounty
subtitle: Follow My Journey
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/bug.jpg
gh-repo: lightorithm/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [bugbounty]
comments: true
---

I have entered the world of Bug Hunting and I'm a convert - I've got no prior experience other than messing around online with a little HTML but not in a malicious or bug hunting way. I have been given the opportunity to carry out training on @Zseano's platform Bugbountyhunter.com and use Barker! Which is a mock social media platform riddled with bugs from XSS to XXE's and more. 

There is a subscription fee for @Zseano's platform and once in he gives you access to his methodology which admittedly at first; I was reading and had absolutely no idea what I was reading, instead I decided to take each bug on one by one and work my way through his methodology rather than loading my brain with too much info. I know there is plenty more to be covered inside his book but it's best to start of on the small stuff and work up, by small stuff I mean XSS and SQL ~ If I can find them after a day then you can! 

Example of XSS are; 

~~~
<script\x0Atype="text/javascript">javascript:alert(1);</script>
<image src=1 href=1 onerror="javascript:alert(1)"></image>
<script>javascript:alert(1)</script\x0A
~~~
**What is XSS Scripting (XSS)?**
Cross-Site Scripting (XSS) attacks are a type of injection, in which malicious scripts are injected into otherwise benign and trusted web sites. XSS attacks occur when an attacker uses a web application to send malicious code, generally in the form of a browser side script, to a different end user. Flaws that allow these attacks to succeed are quite widespread and occur anywhere a web application uses input from a user within the output it generates without validating or encoding it. ~ Taken from github

An attacker can use XSS to send a malicious script to an unsuspecting user. The end user’s browser has no way to know that the script should not be trusted, and will execute the script.

Example of SQL are; 

~~~
' OR 1 -- -
" OR "" = "
" OR 1 = 1 -- -
1' ORDER BY 2--+
1' ORDER BY 3--+
~~~

**What is SQL injection (SQLi)?**
SQL injection is a web security vulnerability that allows an attacker to interfere with the queries that an application makes to its database. It generally allows an attacker to view data that they are not normally able to retrieve. This might include data belonging to other users, or any other data that the application itself is able to access. In many cases, an attacker can modify or delete this data, causing persistent changes to the application's content or behavior. ~ Taken from github

**So, What's Next**

I am going to continue with @Zseano's methodology and practicing on Barker! there are around 70+ bugs to be found and at writing this I have found 11, I will then register on another platform such at YesWeHack! or HackerOne and continue with my Hacking on Tryhackme.com (Add me as a friend on THM LlightOrithm)

There's plenty to do and keep me busy, You can keep tabs on how many bug I have found below - I update this as I go along. 

Bugs Found:

| Bugs | Found | Date |
| :------ |:--- | :--- |
| XSS | 6 | 05/01/2021 |
| SQL | 1 | 05/01/2021 |
| CSRF | 1 | 05/01/2021 |
| SSRF | 0 |  |
| Open Redirect | 1 | 05/01/2021 |
| Application | 1 | 05/01/2021 |
| XXE | 0 |  |
| IDOR | 1 | 07/01/2021 |


![BugBounty](/assets/img/bugbounty.png)


