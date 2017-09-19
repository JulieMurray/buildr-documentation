---
title: Italian
taxonomy:
    category: docs
---

**In Progress**

![Italian](italian-doc.jpg)

Italian is a child theme of the Buildr template. This means it uses the Build.r template and applies Italian specific style via Buildr's built in child theme functionality.

## A note about child themes
The files for child themes are located in the templates/buildr/child folder and are selected in the template admin design side panel.  You can read a full explanation of child theming in Build.r <a href="../style/using-child-themes">here</a>.


## Installing Italian

The following applies to situations where you have already installed the Buildr template on your site or are installing buildr for the first time.

**Step 1** - Download and install the latest version of the <a href="http://www.joomlabamboo.com/downloads/template-downloads?param=buildr">Buildr template</a>.

**Step 2** - Once installed navigate to the template manager and edit the Buildr template.

**Step 3** - Select the Italian example configuration from the load saved settings dropdown.

![Apply Italian](config-1-theme.gif)

After doing this the Italian child theme will be selected and the Italian preset will be set in the preset dropdown list.

Applying the Italian example configuration sets the required theme panel options including the layout blocks used on the demo site in the layout tool.

**Step 4** - Click Save. After clicking save the required assets for the Italian theme will be generated (theme files, css files etc) and will now be available for use on your website.


You can customise the template through the theme control panel, according to the image:


![Apply Italian](config-2-theme-italian.gif)


## Install the Italian quickstart package

If you are starting a new website from scratch we highly recommend installing the Italian quickstart package. This is by far the simplest way to recreate the demo site on your server.

Learn about <a href="http://docs.joomlabamboo.com/getting-started/how-to-install-a-joomla-3-quickstart-package">installing the quickstart package</a>.


## Recreating the Italian demo site

## Description of elements

## Menu

![Menu](menuit.png)


**The offcanvas menu**

![Toggle Menu](canvasita.png)
![Toggle Menu](canvasita2.png)


**Collapsed menu**

The configuration of offcanvas menu is controlled according to the following screen in the theme admin panel

![Collapse](colapsedmenuitalian.png)

**Offcanvas button settings**

The settings used to customize the offcanvas menu are controlled according to the next image.

![Toggle Menu](canvas2ita.png)


**Positioning the offcanvas menu**

The offcanvas menu is located according to the image below. It is enabled to access the website on portable devices.

![Collapse Type](canvas-positionita.png)

**Please note:** The offcanvas menu will only be activated and viewed when accessing the website from a portable device.

To edit the row settings, click the row icon according to the figure below and then go into the style tab. To copy the settings from the demo, set them according to the next image.

![Top Right Row](editcanvasita.png)
![Top Right Row](canvas-style-italian.gif)

To customize the menus, follow the panel according to the image:

![Top Right Row](screen_menu_admin.png)


## Logo

![Logo](logo-ita.png)

The logo in the Utafiti template uses a custom html module published to the logo position.

The markup used in this position is:

	<h1><a href="index.php"><span class="first">Italian</span> <span class="second">Restaurant</span></a></h1>
	
![Logo Default](logoita.png)


Do not forget to create a module for the logo of the mobile version as the image. The other settings are the same as the previous one.

![Logo](logoitamobile.png)

Remember to select all the contents within the text field, and add the link under the picture.

![Logo](link-logoita.png)


## Contact 

![Logo](contact-ita.png)

This module displays a contact phone made with a custom html (icon + text)
![Logo](phone-ita.png)
To view the list of Zen Shortcode tags, access path: Features menu> Tools > Zen Shortcode> tab font icons:

![Logo](shortcode-italian.png)


## Social Icons

The social icons are located in the top-right position of the theme.

### SOCIAL POSITION TOP-RIGHT
![Social Icons](social-head-ita.png)

- The social icons position is within the logo line, according to the image:

![Social Icons](social-head-position.png)


### Social icon content
The content for the social icons can be set in the social panel in the template panel.

![Social icon content](social-icons-settings.png)

### Social Icon appearance

The color, size and other aspects of the social icon appearance can be controlled via the general settings side panel in the template's design panel.

![Social icon content2](screen_social_admin.png)

![Social icon content2](social-icons-settings2.png)


These icons in top-right position are hidden when accessed on smartphones and others devices.


### SOCIAL POSITION COPYRIGHT

![Sociat](social-ita.png)

- This is the thin module in position copyright.
- Leave module title display desabled.


To configure the top slideshow, see the illustration below:

![Social](config-social.gif)



For the Featured module assume the style of the Italian theme, do not forget to use it, according to the image below

Module class suffix: 

      zencenter
	  
	  
![Social](social-css.png)


### Social icons on smaller screens

Accessing the project in portable devices, social icons are like the image:

![Social icon Mobile](social-device.png)


As can be seen in the screenshot above, the social block is designed to be hidden on all screens larger than the phone breakpoint size. The value for the breakpoints can be set in the Layout > Breakpoints section of the General settings side panel.


### Social Icon appearance

The colour, size and other aspects of the social-mobile icon appearance can be controlled via the general settings side panel in the template's design panel.

![Social Icons mobile](social-device-config-ita.png)



## Module Banner Slideshow

![slideshow](banner-ita.png)


To configure the top slideshow, see the illustration below:

![slideshow](confg-bannerita.png)

![slideshow](config-slidehome-ita.gif) 


Slideshow items use standard joomla articles:


![slideshow](content-slide1-ita.png)

![slideshow](content-slide2-ita.png)


The content selection is made according to the image:

![slideshow](config-content-slide-ita.gif) 


## Module Our Menu Specialities


![especialities](our-menu-ita.png)


The module configuration in accordance with the image:

![our services ](config_ourmenu-ita.png)

![our services ](config-ourmenu-ita.gif)

- Please note the number of columns! (3)
- This is the thin module in position grid5.
- Leave module title display enabled.


The content selection is made according to the image:

![slideshow](config-ourmenu2-ita.gif) 


The content that is displayed is generated from joomla articles.

![our services ](conten-out-1-ita.png) 

![our services ](conten-out-2-ita.png) 


For the Featured module assume the style of the Italian theme, do not forget to use it, according to the image below

Module class suffix: 

     zen-centered


![our services ](class-ourmenu-ita.png)

## Module About The Company

![our services ](company.png)


The module configuration in accordance with the image:

![our services ](company-module.gif)

- This is the thin module in position grid9.
- Leave module title display enabled.


The content selection is made according to the image:

![slideshow](company-module-content.gif) 



The content that is displayed is generated from joomla articles.

![our services ](conten-out-1-ita.png) 

![our services ](conten-out-2-ita.png) 


For the Featured module assume the style of the Italian theme, do not forget to use it, according to the image below:

Module class suffix: 

     icon

![our services ](class-company.png) 


## Module People Talk About Us

![the testimony](testimony.png)


This module is constituted with a module Custom HTML (1º) and another module zentools (2º).

1º -The module configuration follows the image:

![our services ](testimony-content.gif)
![our services ](testimony-background.png)

- This is the thin module in position grid13.
- Leave module title display desabled.



2º -The module configuration follows the image:

![our services ](testimony-2.gif)
![our services ](testimony.gif)

- This is the thin module in position grid14.
- Leave module title display desabled.


The content selection is made according to the image:

![slideshow](testimony-3.gif) 



The content that is displayed is generated from joomla articles.

![our services ](testimony-4.png) 

![our services ](testimony-5.png) 



## Module Menu Footer

![menu](foot-menu.png)


This is type module menu in position footer with title enabled.


![menu](menu-foot-conf-ita.png)


## Module Copyright Address

![address](addres.png)


This is type module custom in position copyright with title enabled.

![address](adress-conf-ita.png)

## Module Sample Menu

![address](sample-menu-ita.gif)



The module configuration in accordance with the image:

![menu](sample-menu-config1-ita.gif)
![menu](sample-menu-config2-ita.gif)

- This is formed by two modules in position grid-example-1 called in an article through the tag {loadposition) within an article. 

![menu position](sample-menu-article-position.png)
- Leave the modules with title enabled.

The modules  Starters and Mains following the same configuration.

The content selection is made according to the image:

![slideshow](sample-menu-config-content-ita.gif) 


The content that is displayed is generated from joomla articles.

![our services ](content_menu_smart.png) 

![our services ](sample-content-img.png) 


For the Featured module assume the style of the Italian theme, do not forget to use it, according to the image below:

Module class suffix: 

      menuContent

![our services ](sample-menu-config-class-ita.gif)



## Module Restaurant Map


The background used in page Single Contact is managed by a JB Maps2 module. Where you can change the images,

![our services ](map-single.jpg)


The settings you can see in the images:

![map ](map.gif)
- This is the thin module in position grid17.
- Leave module title display disabled.
