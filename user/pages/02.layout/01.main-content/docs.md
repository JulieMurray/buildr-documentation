---
title: Main content area
taxonomy:
    category: docs
---

It is possible to display more than the traditional main content, sidebar1 and sidebar2 positions in the main content area of the template. However the behaviour of the main content area depends on the kind of modules you are trying to display in the main content block.

## Source ordered content

Zen Grid Framework v4 themes prior to Buildr used a layout template that meant on desktop screens you could have the sidebar1, sidebar2 and maincontent area displayed in any given combination eg left, main, right or left, right, main but on smaller screens the layout collapsed so that the main content was always displayed first. This is called source ordering and in order to do this we use a number clever push / pull classes that handle how the columns are displayed on the page.

This behaviour is unchanged in Buildr and any other themes built using Zen Grid Framework Universal, so long as the following criteria is met:

	Along with the main content block you also need to have either the sidebar1 or sidebar2 module present in the main content area.

When the sidebar1 or sidebar2 block is published along with the main content the template displays only these modules. Any other modules added to the layout for the main block will be ignored.

## Adding other items

If you wanted to avoid this source ordering behaviour then you can simply remove the sidebar1 and sidebar2 modules from the layout and add any other module you prefer to this position. As an example adding a grid1 module position to the main layout will mean that the appropriate content for grid1 will display on the page plus the main content but it will not be source ordered.

