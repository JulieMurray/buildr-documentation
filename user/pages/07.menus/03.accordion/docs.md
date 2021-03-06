---
title: Accordion
taxonomy:
    category: docs
---

Buildr comes with the ability to transform a standard Joomla menu module published to a sidebar position into a collapsible accordion menu.

An accordion menu allows the user to view nested menu items in a menu by clicking on the parent item. Any type of menu item can be used as a parent menu item to open and close the accordion.

The accordion comes with two options that are defined in the template settings:
- A traditional accordion menu which allows a single nested menu item to be open at a time.
- Or a panel menu which allows multiple nested sub level items to be open at a time.

In addition to the template settings below, the menu module needs a menu class suffix of 'zen-accordion' for the correct styling and javascript to be applied to the menu.


### Accordion settings
![General Layout](accordion.jpg)
  

#### Enable accordion
This option needs to be enabled in order to enable the accordion behaviour.

When enabled the required code is output in the tpls/blocks/script.php file.

#### Always open first item
This option ensures that the first item in the accordion menu is always open.

#### Always show active menu item
This options ensures that the active menu item is visible on the page when the page loads.


Accordion is also used for the off canvas collapse menu
----
Please note that the accordion menu is also used if the offcanvas menu is used in the nav collapse setting. (see under the responsive panel in the template settings). This menu is enabled regardless of the enable accordion setting discussed above.