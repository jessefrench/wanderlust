# Wanderlust Hair Salon
This is a fully responsive, beautiful, and modern website I built for a trendy full-service hair salon.

**Link to project:** https://wanderlustsalon.netlify.app

![wanderlust](https://user-images.githubusercontent.com/106822556/177859641-e048e595-e8f3-432a-9510-e2513d9300bc.png)

## How it's Made
**Tech used:** HTML, CSS

This website started with just an image of a layout template. I coded it from scratch knowing I wanted it to be for a trendy hair salon. This was the second static site I had built so I had some experience under my belt and I felt pretty comfortable with most of the key concepts needed to build it out. While looking at the layout template, I quickly mapped out the HTML elements in my head to form a rough draft of the content structure. With that in mind, I got started with writing the HTML making sure to use proper tags that make the most semantic sense and allow for accessibility options like screen readers. With the site content completed, I got to work on styling with CSS. I built out the core layout first using floats, borders, and placeholder images as a first pass, then added color, and pulled in some beautiful images from [Unsplash](https://unsplash.com). From there I just needed to make some minor tweaks and add media queries for responsiveness.

## Optimizations
While I was adding my media queries, I noticed that some parts of the page just didn't look right on mobile no matter how I moved things around. I realized that while vibrant background images look great on bigger screens, they are usually too distracting on small screens. In these sections I decided to simplify things with a solid background color for mobile devices. This made for much more readable text and looked a lot cleaner in general. 

## Lessons Learned
I built this site's layout using floats because other engineers recommended doing so in order to fully understand the box model. At first I thought this must be some kind of joke because I knew there were much better layout building alternatives in CSS like flexbox and grid. But they assured me they were serious so I took them for their word and started on my floats only layout. I quickly found out what they meant. I did so much trial and error coding in order to place things where I wanted, it would be impossible NOT to understand the box model after building this site. Although it would've been much easier to build this site with flexbox or grid, I am glad that I used floats because not only do I now have a deeper understanding of the box model, I can also work with any legacy codebases that may still use floats!
