---
title: CSS3 Animations
taxonomy:
    category: docs
---


The CSS3 effects option adds css3 transitions to entire rows of modules in your template. The animation is triggered when the content becomes viewable on the page. If the content is viewable on page load then the animation is fired straight away whereas if the content is below the fold the animation is triggered as the user scrolls down and the content becomes viewable. 



### Developer notes


Wow.js is used to trigger the animation events. <a href="http://mynameismatthieu.com/WOW/">Visit website</a>

The wow.js file can be found in the js/libs/ folder.

The animate.css less library is a fork of the original animate.css library and can be found <a href="https://github.com/machito/animate.less">here</a>.

The animate less files can be found in the zen/libs/zen/animate folder.	

If the animation library is enabled and your chosen animation has been compiled to the theme's css file it is possible to use the animation in your content or template using classes such as:

	zen-animate fadeInUpBig animated