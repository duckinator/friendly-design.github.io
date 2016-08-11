---
title: Friendly Design
layout: default
class: home
---

Friendly design is an interface design style aiming for minimalism, but
explicitly prioritizing accessibility and understandability.
A significant part of this is explicitly adding design details in areas
for purposes of disambiguation and following guidelines related to
accessibility and usability, such as those from the
[Web Accessibility Initiative](https://en.wikipedia.org/wiki/Web_Accessibility_Initiative)
(WAI).

<h2 id="comparison-flat-design"><a href="#comparison-flat-design">Comparison To Flat Design</a></h2>

Friendly design is related to flat design. I recommend reading
[the Wikipedia page](https://en.wikipedia.org/wiki/Flat_design) as well as
[The Next Web's article discussing flat design](http://thenextweb.com/dd/2014/03/19/history-flat-design-efficiency-minimalism-made-digital-world-flat/).

From The Next Web's article:

_"In laymen’s terms, this means removing stylistic characters such as drop shadows, gradients, textures, and any other type of design that is meant to make the element feel three-dimensional."_

<h2 id="key-differences"><a href="#key-differences">Key
Differences</a></h2>

The key differences between flat design and friendly design are that
friendly design:

* Emphasizes understandability of an interface over minimalism.
* Follows applicable accessibility and usability standards and guidelines,

Throughout the rest of this document, I'll further expand on these points.

<h2 id="following-standards-guidelines"><a href="#following-standards-guidelines">Following Accessibility and Usability Standards and Guidelines</a></h2>

All interfaces, not just websites, should follow applicable
[Web Accessibility Initiative](https://en.wikipedia.org/wiki/Web_Accessibility_Initiative)
standards and guidelines, including the [Web Content Accessibility Guidelines](https://en.wikipedia.org/wiki/Web_Content_Accessibility_Guidelines)
(WCAG).

<h2 id="common-failures"><a href="#common-failures">Common Design Failures, And How To Avoid Them</a></h2>

An extremely common failure when using flat design is having insufficient
contrast between text and background colors. To that end, interfaces
should follow the
[WCAG 2.0 guidelines for use of color (1.4.1) and contrast (1.4.3)](http://www.w3.org/TR/WCAG/#visual-audio-contrast).
You can use
[Lea Verou's contrast ratio checker](https://leaverou.github.io/contrast-ratio/)
for checking compliance with the latter.

This means is that wherever color is used to convey something to
the user, something else should be used as well &mdash; e.g.,
underlining links or outlining buttons a certain way.
This ensures interfaces make sense to as many people as possible.

A related common failure of interfaces is simplifying the design to
the point that users can't differentiate between elements.
E.g., giving buttons and text inputs the same styling: a border, and
nothing else. This should be avoided to the extent it is possible.

Meeting the WCAG 2.0 guidelines for contrast ensures the readability
of the interface.

