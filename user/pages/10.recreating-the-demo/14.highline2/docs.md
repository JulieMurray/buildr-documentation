---
title: Highline2
taxonomy:
    category: docs
---

**In Progress**

<img src="http://www.joomlabamboo.com/images/new/highline2/highline2-responsive.png" alt="Highline2" />

Highline2 is a child theme of the Build.r template. This means it uses the Build.r template and applies Highline2 specific style via Build.r's built in child theme functionality.

## A note about child themes
The files for child themes are located in the templates/buildr/child folder and are selected in the template admin design side panel.  You can read a full explanation of child theming in Build.r <a href="../style/using-child-themes">here</a>.


## Installing Highline2

The following applies to situations where you have already installed the Buildr template on your site or are installing buildr for the first time.

**Step 1** - Download and install the latest version of the <a href="http://www.joomlabamboo.com/downloads/template-downloads?param=buildr">Buildr template</a>.

**Step 2** - Once installed navigate to the template manager and edit the Buildr template.

**Step 3** - Select the Highline2 example configuration from the load saved settings dropdown.

![Apply Highline2](apply-Highline2.gif)

After doing this the Highline2 child theme will be selected and the Highline2 preset will be set in the preset dropdown list.

Applying the Grid 4 example configuration sets the required theme panel options including the layout blocks used on the demo site in the layout tool.

**Step 4** - Click Save. After clicking save the required assets for the Highline2 theme will be generated (theme files, css files etc) and will now be available for use on your website.


## Install the Highline2 quickstart package

If you are starting a new website from scratch we highly recommend installing the Highline2 quickstart package. This is by far the simplest way to recreate the demo site on your server.

Learn about <a href="http://docs.joomlabamboo.com/getting-started/how-to-install-a-joomla-3-quickstart-package">installing the quickstart package</a>.


## Recreating the Highline2 demo site

## Description of elements

## Menu

![Menu](menu.jpg)

**The expanded menu**

![Toggle Menu](toggle-menu.jpg)


**Collapsed menu**

The Highline2 demo displays the menu in a collapsed state at all screen sizes. This setting is controlled via the nav collapse breakpoint found in the templates layout sidepanel.

![Collapse](collapse.png)

The type of collapsed menu used is determined by the mobile menu type option. The toggle menu or off canvas menu are ideal for use in the Highline2 template.

![Collapse Type](collapse-type.png)

**Toggle button settings**

The text used for the toggle menu button and the text used to close the menu when it is open is controlled via the menu panel in the template settings. The style of the button used is also controlled in this area of the template settings.

![Toggle Menu](toggle-menu.jpg)


**Positioning the toggle trigger**

The toggle menu is displayed in the template layout when the toggle-menu layout block is dragged into the layout. The Highline2 child theme places the toggle-menu block int he top-left block in the layout area.

![Collapse Type](toggle-trigger.png)

**Please note:** The menu block also needs to be in the layout area for the toggle menu to work in this instance.

The top left row uses the following settings:

![Top Left Row](top-left-settings.png)


## Logo

![Logo](logo.jpg)

The logo in the Highline2 template uses a custom html module published to the logo position.

The markup used in this position is:

	<p class="zen-center"><img src="images/logo.png" alt="Logo" /></p>

To create the correct positioning the module uses the following module class suffix:

	minusbottom60 minustop30

- minusbottom60: moves the content below the logo up by 60px.
- minustop30: moves the logo module up 30px

## Social Icons

![Social Icons](social-icons.jpg)

The social icons in the top right hand corner are rendered via the template.

### Social icon position
To control the position of the social icons navigate to the design panel in the template settings. The social icons can be placed anywhere in the template layout. The demo features the social icons displayed in the top-right block.

![Social icon position](social-icons-position.png)

### Social icon content
The content for the social icons can be set in the social panel in the template panel.

![Social icon content](social-icons-settings.png)

### Social Icon appearance

The color, size and other aspects of the social icon appearance can be controlled via the general settings side panel in the template's design panel.

![Social icon content2](social-icons-settings2.png)


### Social icons on smaller screens

On the demo when the template is viewed on smaller screens you will have noticed that the social icons are no longer displayed on the top right of the screen, but are moved below the logo in a white row that stretches across the screen.

![Social icon Mobile](social-icons-mobile.jpg)

This is achieved by adding the social-mobile block to the top row.

![Social icon Mobile](social-mobile.png)

As can be seen in the screenshot above, the social block is designed to be hidden on all screens larger than the phone breakpoint size. The value for the breakpoints can be set in the Layout > Breakpoints section of the General settings side panel.


### Social Icon appearance

The color, size and other aspects of the social-mobile icon appearance can be controlled via the general settings side panel in the template's design panel.

![Social Icons mobile](social-icons-mobile.png)


## Banner slideshow

![slideshow](slideshow.jpg)


## Zentools2 Isotope

Zentools2 module published to the grid1 position.
![slideshow](isotope.jpg)