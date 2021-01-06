---
layout: post
title: BugBounty
subtitle: Follow My Journey
gh-repo: lightorithm/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [bugbounty]
comments: true
---

So, i managed to get a little github.io page - You will find everything to do with BugBounty and Ethical hacking Im currently on a couple of platforms for both and will update as I go along. Main BugBounty testing platform is BARKER! hosted my Bugbounty.com and run by @Zseano. 

**BugBounty.com**

I have recently started BugBounty 2021 and very luckily got access to @Zseano platform BARKER! in which you can experiment on a live platform and hunt bugs whilst going through Seano's Methodology too. 

Here's a useless table:

| Bugs | Found | Date |
| :------ |:--- | :--- |
| XSS | 1 | 05/01/2021 |
| SQL | 1 | 05/01/2021 |
| CSRF | 1 | 05/01/2021 |
| SSRF | 0 | 05/01/2021 |


How about a yummy crepe?

![Crepe](https://github.com/LightOrithm/lightorithm.github.io/blob/master/assets/img/2021-01-06%2012_38_23-Learn%20about%20web%20application%20vulnerabilities%20and%20how%20to%20find%20them%20on%20bug%20bounty%20p.png)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
