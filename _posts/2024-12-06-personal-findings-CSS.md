---
title: "Personal Findings with CSS"
date: 2024-12-06
---

# Personal Findings with CSS
It's been a month since I finished The Odin Project's section on [Intermediate HTML and CSS](https://www.theodinproject.com/paths/full-stack-javascript/courses/intermediate-html-and-css)

## 1. CSS is not so simple
I always remember friends and people I admire, say the words, "CSS is not a programming language".

Now, this may or may not be true, and I'll leave that for you to decide and scour the internet for the many heated debates.

But one thing for sure is that perception has hindered me from really taking the time to learn CSS. I always felt that it should be easy and I would be better off using my time to learn technologies more *worthy* of my time. And that a few selectors and attributes are all I need to remember.

How wrong I was. CSS is not easy. And the constant high brow look on it, makes it hard to give it the respect, it quite frankly deserves. Making webpages render correctly on multiple browser engines, screen sizes and devices is no small feat. CSS does a lot of heavy lifting and I think taking time I dig past the surface has been very beneficial.

## 2. Tables and Forms are hard.
Oh boy, I was not expecting this. But it's true, tables and forms, two seemingly easy things to design, are not that easy indeed. 

Using CSS to style forms can be hellish, some HTML form inputs refuse to be styled (e.g date picker input which is different with every device/browser)

True customization might just need you to be build your own implementation of the input using JS.

Things like pseudo-elements simply don't work on input elements, and often need wrapper divs around them. (These can be useful to toggle a message to the user about the form)

So the next time, you find that an input element doesn't look the way you want, pause, and take a look at the documentation.

## 3. CSS has come a long way

CSS has been getting a lot of features that make it genuinely powerful. CSS variables help keep track of all those arbitrary hex codes and even set up a light/dark mode (a must these days).

CSS Grid is just on another level. It gives you the ability to truly layout your webpage. There's been talks by Jen Simmons on Intrinsic design that I found really cool and a step above the ideas of Responsive design everyone seems to blab about.

You don't really every have to use floats anymore. (I think)

CSS forms have pseudo-classes such as invalid that can help figure out if your form has inputs that the client hasn't typed in correctly, which you can use to display a message. This does NOT mean you don't have to handle the data and have your own way to validate the data on the backend!

But it does save you some Javascript.

And I think the point is, CSS is ever-changing, learning to adapt to the requirements of developers and the web. You can never really sit back and think you understand it all.

And that's okay.

## 4. A bit more on intrinsic design

Intrinsic design is really just the idea of writing your CSS so that the browser just knows (intrinsically) how to best render the page.

Now this goes against the grain of responsive design, which often has this push towards writing CSS mobile-first and then use media queries and breakpoints to alter the layout for different viewports.

Now, CSS grid comes in incredibly clutch, to make responsive designs its ability to fit thing by simply specifying the number of columns / rows you want your page to use and relative units like fr really help it work on any page.

CSS grid also gives amazing precision, allowing you to place down elements exactly where you want.

It's awesome and I wish I learned it sooner. Trust me it's not just another flexbox. In fact, flexbox and Grid work really well together, so learn both, and you'll thank yourself later.


## Thought on the TOP intermediate HTML & CSS
This part of the course was jarring to me, I had just finished building a calculator using vanilla HTML, CSS and JS and was excited to dive deep into the world of JS. So the sit down and push to learn more CSS, wasn't that exciting, if I'll be honest. 

But I learned a tonne. Some things made me better at writing up code. The section on using Emmet has transformed the way I write up HTML. The stuff on CSS grid, I think will be used by me, for a long time coming. And now I won't be too unhappy if I can't get a form designed my way easily, in fact, I might just lean towards a prebuilt library from the start, because, why reinvent possibly the most valuable page in your site when there's people who've built and tested great looking and, more importantly, functional forms?

There's still a lot more I need to learn, especially on making things work on different screen sizes and organizing my css better. But this course helped me tremendously, and I was pretty happy with the page I built using simple vanilla CSS and HTML. Check it out [here](https://abeeto.github.io/odin-admin-dashboard/)

That's all for now, see ya.
abeetos



