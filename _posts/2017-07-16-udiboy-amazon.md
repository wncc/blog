---
layout: post
title: Meet's internship at Amazon '17
categories: internship
tags:
  - mercari
  - internships
imagefeature: "http://summerblog.insightiitb.org/wp-content/uploads/2017/06/amazon1-1.jpg"
imagecreditlink: "http://www.spreadeffect.com/blog/improve-website-speed/"
comments: true
mathjax: null
featured: true
published: true
author_name: Meet Udeshi
author_website: http://udiboy1209.github.io
author_image: https://avatars1.githubusercontent.com/u/7384411?s=400&v=4
author_description: Automater | Tinkerer | Nolan Fan | Movie Enthusiast
---

*The following has been adapted from the insight-iitb. Access the original version [here](http://summerblog.insightiitb.org/amazon-meet-udeshi/).*

# Intern Blog

As I sit on my desk in Amazon Bangalore Office, with two widescreen monitors and a Macbook pro, I wonder what am I doing. I mean it’s 12:30 in the afternoon here, I just walked in half an hour ago, and I’m writing my intern blog. What I’m really doing is waiting for a review on a wiki I wrote describing two possible approaches to the problem given to me to solve for the duration of my internship. It’s the third time I have reminded my mentor to review it, but he doesn’t seem interested at all and is busy in back to back meetings since yesterday. Maybe that’s what it’s like to work in large MNCs, lots of planning and little implementation. Here goes my two cents on the Great Customer-centric Amazon Company summer internship.

{: .center}
![Gear](http://summerblog.insightiitb.org/wp-content/uploads/2017/06/amazon1-1.jpg "Gear"){:style="max-height: 500px;"}

# Selection process
Amazon comes to IITB one, two months into the season when the intern fever has settled down. It was open for all departments and had no CPI cut-off, which is how an EE Dual 7-pointer got in :P. For a person like me, that was enough to make me apply for the intern. The interview was like any other Software Dev interview would be – an online selection test on DSA and multiple one-on-one rounds of DSA questions. The interviewers we had were pretty indulgent and interactive while asking questions, up to the point where it almost felt like a discussion.
In my case, I had no idea going into the one-on-one round that a Depth-first Search uses stacks and also how it is implemented with stacks (I can hear you laughing at me). The interviewer wasn’t bothered much by the fact and he helped me derive the whole implementation by asking me the correct questions. The next round was a similar set of questions, and went well for me and I eventually got selected! Yay!
# Pre-Internship Time
Cutting to pre-summer time, conveniently skipping the infi requests of unlimited Prime memberships and free gift vouchers from friends and family, it’s a very big wait till Amazon HR people will first contact you. At least that’s what happened with all the people going to Bangalore. I wouldn’t blame them though, because Amazon is probably overworking their HR team with the hiring spree this year. In the end, they did get everything done though – Flight tickets, Hotel accommodation for 15 days, Airport pickup.
The internship starts a bit late into the summer holidays, so you get about 2 weeks of free time after your endsems. All you are expected to do in this time is be in email contact with the HR team. We waited too long to contact the HR team and found out about these 2 weeks of free time pretty late.

# It’s still Day 1
They throw around this phrase here like dirt. All it means is every employee is expected to work everyday like it’s their Day 1, and they have a long way to go still. My day 1 was pretty bummed out, actually :/ . I hadn’t expected anything better though, with multiple boring HR sessions, getting your ID card photo clicked, and what not. It wasn’t all bad because we did each get a Macbook as our work laptop.
Well, then came the development environment setup. They never make that one an easy job. It took two long days to install all the tools, acquire permissions in multiple groups (Unix groups), set up a cloud desktop, and get it all working together. It actually seems pretty impressive, because when you think about it they have set up a pretty robust system which any company of this scale would require. In the first week we found out about how development actually gets done in Amazon. We found out about what pipelines they use for stage-by-stage deployment, how they test at every stage, and how mishaps are handled. Yea, its not as simple as just pushing code to the server. There’s Alpha and Beta stages in between which every code change has to pass through. And they have automated tests hooked up to every stage, which if they fail will stop the deployment automatically!
It all feels surreal when you think about the sheer scale any single piece of code will be affecting. As an example, let me tell you about my team.
# My team
{: .center}
![Gear](http://summerblog.insightiitb.org/wp-content/uploads/2017/06/amazon2-1.jpg "Gear"){:style="max-height: 500px;"}

Transport Financial Systems, or TFS as its more passionately called, manages the accounting of all financial aspects of the transport expenses Amazon makes. Transport here refers to shipping of Amazon products, from anywhere to anywhere else, done by multiple different couriers. Millions of products are shipped everyday, generating hundreds of thousands of invoices from couriers. These all need to be properly audited and accounted for, and then paid. But we aren’t accountants, we are developers who automate this whole accounting process! While going through the codebase (or deep-diving as they like to call it), we were able to look at their databases and workflow queues each with millions of entries of product-wise accounting of every little cost which went into transport of every product. Surreal, right!

# My project
What my team does is a pretty long and boring story, and the task I’ve been assigned is a little automation to be done on their existing system to make things easier for the existing developers. It has to deal with the accounting of USPS based shipments.
The work essentially involves working with SQS queues to filter and keep some messages on standby for certain duration, then redrive them back to the main flow. Everything here extensively uses AWS, obviously. And if nothing, I’ll surely learn how to use AWS services very efficiently. Because that is exactly what I’ve been planning for the past week XD . How should we store the messages? what data model would be most efficient? what are the pros and cons of the two approaches? I’ve been wanting to tell them, let’s just implement it and see, but that may invite unnecessary negative criticism. Well, honestly that’s what has bored me up till now, probably because we all are so used to the Implement-it-then-analyse-it strategy that we so passionately follow in college. Maybe that’s why the people here also tell me to not trust StackOverflow, and to always deep-dive into the documentation. But they’re the same people who tell me vim kills my productivity and you lose all your trust in them at that point 😛 . I mean, I’m writing this frickin blog in vim, and they tell me to code in IntelliJ.
No more ranting, I promise
Enough with the rant, now. While there is enough to sulk at, there’s loads to enjoy in this place too! Bengaluru city is awesome for those who like partying, and night-life here is pretty cool! Amazon teams go on one-day office outings to some place nearby – we were lucky enough to go to Club Cabana, and spend a day full of bowling, pool-side fun and other indulgences… :D.amazon2
The weather here is surprisingly cool and pretty nice for walks in the park, if you have the right company. You would’ve been sweating it out in Mumbai this time of the year, when here in Bengaluru you don’t even need the fan at night. And there are a lot of pretty parks in and around the city. We’ve pretty much been following Google Maps for place recommendations and we’ve not been disappointed!
If not for the place, Bengaluru will be awesome simply for its company of people because aadha insti bangalore me intern karta hai (Half the people in insti are interning at Bangalore) is what I’ve heard. I’ve even met up with seniors who have passed out and joined their new company here.
In summary, I’d just like to say that apart from the work, I’ve been pretty satisfied with Amazon as a company, and this city. Maybe it’s just that Software Dev isn’t meant for me. It’s been a unique experience until now and I hope this intern surprises me a bit more!