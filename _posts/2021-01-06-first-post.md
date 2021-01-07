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

I have entered the world of Bug Hunting and I'm a convert - I've got no prior experience other than messing around online with a little HTML but not in a malicious or bug hunting way. I have been given he oppurtinuty to carry out training on @Zseano's plaform Bugbountyhunter.com and use Barker! which is a mock social media platform riddled with bugs from XSS to XXE's and more. 

@Zseano gives you access to his methedology which admitantly at first I was reading and had no clue what I was reading, instead i decided to take each bug on one by one and work my way through his methodoloty rather than loading my brain with too much info. I know there is plenty more to be covered inside his book but it's best to start of on the small stuff and work up, by small stuff I mean XSS and SQL ~ If i can find them after a day then you can! 

Example of XSS are; 

~~~
<script\x0Atype="text/javascript">javascript:alert(1);</script>
<image src=1 href=1 onerror="javascript:alert(1)"></image>
<script>javascript:alert(1)</script\x0A
~~~

**What's Next**

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


