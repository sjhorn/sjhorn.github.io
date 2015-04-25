---
layout: post
title:  "The 8-mile effect"
date:   2015-04-25
comments: true
---

![](http://www.universalstudiosentertainment.com/assets_c/2010/04/61109281_8%20Mile_800x445-thumb-800x445-573.jpg?01AD=3_lniGCFj_hjJEB-6zC7F8JD-kTHdtZsx9nsBk0WuKlHi1mFkx4X5Aw&01RI=D674B6A53BCC86E&01NA=na)

<p class="intro"><span class="dropcap">D</span>
eveloping software has a fair share of challenges. Choosing the right tools, the right platform, the build pipeline, unit testing, stress testing, security...
</p>

But none of these compare to the challenge that emerges when choosing the **right** features to do first. 

Over the last decade I have worked with various internal and external stakeholders and one thing that seems to get in the way of choosing the **right** features is best expressed by Eminem's performance in the movie [8-mile](https://youtu.be/axGVrfwm9L4?t=53)

    ... Look, if you had one shot, or one opportunity
    To seize everything you ever wanted. one moment
    Would you capture it or just let it slip...
 
Everybody wants **their** feature included, because otherwise it won't get another chance.

The interesting side effect of this is the followup water cooler conversation about how software projects are never:

 * delivered on **time**,
 * to a **satisfactory level of completion**, 
 * or ever have the infamous **phase 2** where the rest of the features get delivered. 

The interesting thing about these comments is the way they form a self-fulfilling prophecy for the next attempt to do a software development lifecycle. 

### Delivered on time
The [Iron Triangle](http://en.wikipedia.org/wiki/Project_management_triangle) of project management demonstrates that only two out of three contraints of cost, features(scope) and time(schedule) can be fixed. Or expressed in another way a change to one of the items effects the other two. ![](http://upload.wikimedia.org/wikipedia/commons/a/a6/The_triad_constraints.jpg)

So given time is fixed and features are being added, cost will increase. For fixed budget software developemnt this is not an option so ultimately time is impacted. 

To deliver on time cost and scope need to be fixed. 


### A satisfactory level of completion

The drive to ensure features are included in software leads to two side effects. 

 1. Extended **analysis** and **design** lead time leading to analysis paralysis and/or abtrirary trade-off based on what can be completed the quickest. 
 2. Late and incremental addition of features to a constrained design. An effect similar to the way wires are run in the picture below. 
 ![](http://www.ekantipur.com/uploads/tkp/news/2010/gallery_10_06/CROSSWIRE_20101007084334.jpg)
 
Both of the side effects  lead to results that aren't considered satisfactory when software ships.

### The infamous Phase 2

The folklore that I have seen built about about the idea that *there is no phase 2* has only helped put more pressure on the first phase of software development. The harvard business review writer Jeff Gothelf even wrote an article further supporting the folklore - [The Biggest Lie in Corporate America Is Phase 2](https://hbr.org/2012/05/the-biggest-lie-in-corporate-a)

## So what can we do ?

The work of pioneers in the agile process dating back to [1957](http://en.wikipedia.org/wiki/Agile_software_development#History) has lead to a popular movement around iterative development, lean methodology and the concept of focus using the theory of constraints. These movements are the next steps on our journey to a better way. 

### Iterative Development
Iterative development encourages a strong feedback loop of creating usable artefacts and attaining feedback through quantitative (eg. digital analytics) and qualitative (eg. user testing, focus groups, surveys) methods. 

This helps validate the feature choices made in each iteration and helps test **gut** decisions or forecasted outcomes early. 

### Lean Methodology
The popular book [the lean startup](http://theleanstartup.com/book) by Eric Ries has taken the concept of choosing features back to its entrepreneurial roots. Eric promotes the idea of clearly establishing the problem and then choosing a [Minimum Viable Product (MVP)](http://theleanstartup.com/principles) that can begin the process of **learning** if product and features provide a useful solution. 

### Focus and the theory of constraints

Eli Goldratt in his popular business novel [The Goal](http://bit.ly/1yYUsdE) presents the idea that when problem solving we should not always optimise the entire workflow. Rather we should focus first on the bottleneck or constraint. In his other presentations he concentrates this concept in a decision making process he names the [Theory of Constraints (TOC)](http://en.wikipedia.org/wiki/Theory_of_constraints). With the tools he provides it is possible to take a large set of data and intuitive insights(i.e. "gut feel) and produce a set of prioritised steps to lead to a goal. For choosing features to learn from first - these tools can work well for individuals and teams trying to get started and make ongoing decisions. 

## Closing thoughts

You will regularly encounter peers and stakeholders who want to add their ideas and features to your software. You will also encounter the fear of missing the opportunity to get that crucial item into the next release. Now you know this is the "8-mile" effect and there are tools to help. With Lean-MVP and TOC you are in a better place to prioritise the features based on a clear understanding of the problem and the learning process to provide the most useful software.


![](http://lh6.ggpht.com/_RR5gzeM2qgU/TaxBEuynOgI/AAAAAAAAAME/c1knMs_T-UM/bottleneck-subordinate-to-bottleneck.png?imgmax=800)