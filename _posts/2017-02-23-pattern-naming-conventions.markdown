---
layout: post
title:  "Pattern Naming Conventions in Web Design"
url: "/pattern-naming-conventions-web-design-"
date:   2017-02-23 10:00:00
categories: patterns
---

Unlike [CSS selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors) – [classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors) and [ids](https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors) – that no one except designers or developers see, some of us are exposing our [design systems and their naming conventions](http://patternlab.io/) to clients during projects. Names of design elements are exposed in a way that they weren't before. But do names really matter to our clients?

If you've spent time working with any type of complex system, you know that naming things is important. Relationships and hierarchies are expressed through names. If [naming conventions](https://en.wikipedia.org/wiki/Naming_convention_(programming)) don't work or aren't easy to follow, our understanding of the system falls apart. And that makes it hard to use and maintain.

Pattern based design is an attempt a systematizing the design and front-end development of websites. In the [Atomic Design](http://atomicdesign.bradfrost.com/) system naming conventions are an attempt to make the structure of the system more understandable. Single HTML elements are atoms, groups of elements are molecules, and sections are organisms.

It works OK in practice. But I've found from experience that some clients struggle with the [abstraction](http://atomicdesign.bradfrost.com/chapter-2/). It can also be difficult for me to explain and a time consuming part of a meeting that we'd both like to keep short and to-the-point. My clients have mostly been concerned with the larger parts of the system: templates and pages, sometimes sections. But they're mostly underwhelmed reviewing block level elements.

So I don't use abstract naming conventions or even expose them to lower-level patterns other than font choice and sizing. 

I have my own light-weight pattern library tool. While inspired by Atomic Design and Pattern Lab, it's got a smaller footprint. Rather than abstract names at the top level of the system – atoms, molecules, organisms – I use more literal names. My top-level pattern categories are: elements, blocks, and sections. This naming convention is an attempt at more semantic naming. 'Elements' for example, correspond to basic HTML elements like '<p>'. Content blocks are just 'blocks'. And sections are . . . 'sections.'

While I spend a little bit of time going over how I work with clients, I'm not that concerned with making sure they get the metaphor. I'd rather spend the limited time I have to get feedback on looking at the things they want to see in a context that's familiar to them.

The best thing about designing and developing with modular systems is their flexibility. It's easy to use the underlying principles of something like Atomic Design but adapt them for the types of projects you work on. Look at the variety of systems out there: [Pattern Lab](http://patternlab.io/), [Lightning Design System](https://www.lightningdesignsystem.com/), MailChimp's [Pattern Library](https://ux.mailchimp.com/patterns). If you're considering a pattern based approach to front-end design, don't feel like you need to be locked into a specific tool. And it's really not too difficult to develop your own.




