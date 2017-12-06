---
layout: essay
type: essay
published: true
title: "Food for Thought"
date: 2017-12-05
permalink: essays/food-for-thought.html
labels:
  - Software Engineering
  - Deisgn Patters
  - Gang of Four
---

When you walk into any supermarket worth its salt, you start to notice many things about the layout that seem to be shared across all supermarkets. Produce is near the front often next to flowers, candy and other sugary things by the cashier for impulse buys, eggs and dairy (things you probably came in for in the first place, are in the back making you walk past everything else, and so on and so forth. It’s something I noticed back in the day and wondered why that was. These things all serve to fill a purpose: to maximize what you buy. Clearly it must work or people think it works because its like that nearly everywhere. There are probably other influcences such as needing to stock perishable dairy products from the back so that older things are in the front, but the layout is so widespread that it’ s become a standard. Much like there is a commonly accepted and proven layout for supermarkets, there are commonly accepted and proven designs for programming. 

Much like the millions of people that have wondered why produce is placed near the front, some experienced software engineers noticed that certain models of programming showed up in code. It really was only a matter of time before someone wrote a book. Originally I was told to read it in preparation for an internship, and I just could not grasp that these were general patterns that you could just find and not necessarily code to like an algorithm. It walked through the process of creating a text editor and I was just like “jeez really, this is what we’re making here? We’re making this now?” Like I said, I couldn’t grasp.

Sometimes you put the cashiers by the exit because it would be stupid not to. So sometimes you have a design pattern because whatever you’re making just exists in that form. If you have something that only needs to occur once, you have a singleton. There’s no need to make more, why do it? The singleton was probably an observed design pattern rather than a derived one, since it seems to be fairly simple. Patterns like iterator and private class just serve basic, required functions. I’ve used all of these patterns in my code simply because they were the most obvious or necessary thing to do at the time.

Sometimes you put the butcher’s in the back because you don’t want to wheel fresh stock through the store, and sometimes you implement a design pattern because it’s in the best general interests of your code. Design patterns like object pool and objserver can make your code run better and can make development far easier by avoiding unnecessary work. I’ve used object pool in ICS 111 when I had to make a snake game and coded in a way that made CPUs burst into flames, and used observer in meteor when having to update every page would make me want to burst into flames. In the case of 111, it was a fix, or maybe a crutch, to something was awfully coded, I’m sure, but it certainly was one case of winging something up on the fly that turned out to be one of these fabled “design patterns.”


Sometimes you put the mattresses next to the meat & poultry because you don’t know how to run a store, but one time you heard that eating makes people sleepy. Similarly, not benefitting from a prototype or proxy and still using them is a waste of materials. Naturally, these were some things you try out early in coding and facepalm later when you realize some T.A. looked upon your code with nostalgia and frustration thinking to themselves “I remember when I was that dumb...” Sometimes you can get used to using inefficient code and use a design pattern when it might not be the best thing to have. Just because these patterns exist doesn’t mean they’re still relevant or ideal for the purpose you need in today’s world. 

Sometimes you lay out the supermarket the way everyone else does because that’s what people expect you to do, and they don’t have to remember an entirely different layout for every store. With design patterns, you can find yourself limited if you don’t innovate, but if you implement commonly used or studied design patterns then it’ll make anyone who is familiar with them more accustomed to your code more quickly. In a department with high turnover rate or vital code understanding what you need to maintain and update is of utmost importance, and using an expected or predictable design pattern can help speed that process along. I’ve used design patterns in my work mostly unknowingly, but I think having some kind of standard to expect is helpful and better than nothing. 
