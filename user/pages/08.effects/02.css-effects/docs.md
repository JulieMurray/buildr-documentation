---
title: Row Animation
taxonomy:
    category: docs
---

The row animation makes it possible to reveal content on the page via the use of fancy effect such as bounce in, fadeIn etc. Content for each row is revealed when it becomes visible - either on page load or as the user scrolls.

The row animation setting can be found in the effects group, in the style tab for the row setting that you want to target.

![Animations](effects.png)

## Animations available

Animations include:

- bounceIn
- bounceInLeft
- bounceInRight
- bounceInUp
- fadeIn
- fadeInDown
- fadeInDownBig
- fadeInLeft
- fadeInLeftBig
- fadeInRight
- fadeInRightBig
- fadeInUp
- fadeInUpBig
- flash
- flip
- flipInX
- flipInY
- lightSpeedIn
- pulse
- rollIn
- rotateIn
- rotateInDownLeft
- rotateInDownRight
- rotateInUpLeft
- rotateInUpRight


## Adding effects to single modules

It is possible to add effects to specific modules in the template using the builtin effects system. To do this though you need to follow these steps:

1. In the template settings go to effects and make sure that css3 effects are enabled for the template.

2. In the design panel in the template settings go to the debug row and select the effect you want to use eg fadeInUpBig. We chose the debug row here because it's generally not used to display content to your end users. If you are using debug then you will need to select a different unused row of modules. This is necessary because it adds the required css for the animations in your theme css file and also triggers the use of the required javascript to trigger the animation.

3. Click save which will recompile the css for your theme and include the css for the effect you just chose.

4. Now go to the module you want to apply the effect to and add the following class to the module class suffix: zen-animate fadeInUpBig

After following these steps you should see the fadeInUpBig animation applied to the module in question.


## Developer notes


- Wow.js is used to trigger the animation events. <a href="http://mynameismatthieu.com/WOW/">Visit website</a>
- The wow.js file can be found in the js/libs/ folder.

- The animate.css less library is a fork of the original animate.css library and can be found <a href="https://github.com/machito/animate.less">here</a>.

- The animate less files can be found in the zen/libs/zen/animate folder.	

If the animation library is enabled and your chosen animation has been compiled to the theme's css file it is possible to use the animation in your content or template using classes such as:

	zen-animate fadeInUpBig animated