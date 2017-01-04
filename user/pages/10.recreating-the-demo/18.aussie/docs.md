---
title: Aussie
taxonomy:
    category: docs
---

**In Progress**

![Utafiti](theme_devices.jpg)

Aussie is a child theme of the Buildr template. This means it uses the Build.r template and applies Aussie specific style via Buildr's built in child theme functionality.

## A note about child themes
The files for child themes are located in the templates/buildr/child folder and are selected in the template admin design side panel.  You can read a full explanation of child theming in Build.r <a href="../style/using-child-themes">here</a>.


## Installing Aussie

The following applies to situations where you have already installed the Buildr template on your site or are installing buildr for the first time.

**Step 1** - Download and install the latest version of the <a href="http://www.joomlabamboo.com/downloads/template-downloads?param=buildr">Buildr template</a>.

**Step 2** - Once installed navigate to the template manager and edit the Buildr template.

**Step 3** - Select the Aussie example configuration from the load saved settings dropdown.

![Apply Utafiti](config-style.gif)

After doing this the Aussie child theme will be selected and the Aussie preset will be set in the preset dropdown list.

Applying the Aussie example configuration sets the required theme panel options including the layout blocks used on the demo site in the layout tool.

**Step 4** - Click Save. After clicking save the required assets for the Aussie theme will be generated (theme files, css files etc) and will now be available for use on your website.


You can customize the template through the theme control panel, according to the image:


![Apply Utafiti](config-oder-option.gif)


## Install the Aussie quickstart package

If you are starting a new website from scratch we highly recommend installing the Aussie quickstart package. This is by far the simplest way to recreate the demo site on your server.

Learn about <a href="http://docs.joomlabamboo.com/getting-started/how-to-install-a-joomla-3-quickstart-package">installing the quickstart package</a>.


## Recreating the Aussie demo site

## Description of elements

## Menu

The Aussie theme has two versions of the menu layout, configured as follows:

**1 -** The first version is MENU >> LOGO >> MENU >> SEARCH 

![Menu](topo-padrao.png)

**2 -** The second version consists of MENU >> SEARCH >> LOGO (below)

![Menu](menu_alternative.png)



To configure the menus you need to configure the following:

- Select the type of layout you want from the themes menu, according to the image below:

![Menu](menu1.png)

- It is also necessary to select the type of menu you want by default, according to the image below

![Menu](menu2.png)

Within each menu, you need to enter these classes:

**Menu Default**

![Menu](classe-default.png)

![Menu](class_color_default.png)


**Menu Alternative**

![Menu](class_alternative.png)

![Menu](class-color.png)

**The offcanvas menu**

![Toggle Menu](menu_canvas.png)
![Toggle Menu](canvas-open.png)


**Collapsed menu**

The configuration of offcanvas menu is controlled according to the following screen in the theme admin panel

![Collapse](colapse_menu.png)

**Offcanvas button settings**

The settings used to customize the offcanvas menu are controlled according to the next image.

![Toggle Menu](offcanvas_adm.png)


**Positioning the offcanvas menu**

The offcanvas menu is located according to the image below. It is enabled to access the website on portable devices.

![Collapse Type](screen_offcanvas.png)

**Please note:** The offcanvas menu will only be activated and viewed when accessing the website from a portable device.

To edit the row settings, click the row icon according to the figure below and then go into the style tab. To copy the settings from the demo, set them according to the next image.

![Top Right Row](screen_config_row.png)
![Top Right Row](config_style_row.gif)

To customize the menus, follow the panel according to the image:

![Top Right Row](screen_menu_admin.png)


## Logo

The logo in the Aussie template uses a custom html module published to the logo position.


The logo is presented in two forms, one for each menu:

**1 -** Menu default - With the default menu, the logo is used as the image

![Logo](logo1.png)

	<h1><a href="index.php"><img src="images/democontent/logo-aussie.png" alt="logo" /></a></h1>
	
![Logo Default](logo_img.png)

**2 -** Menu alternative - With the alternative menu, the logo is used as html

![Logo](alternative-logo.png)

	<h1><a href="index.php">{zen-paw}{/zen-paw} Aussie</a></h1>

The logo consists of an icon and text. The icon is displayed using syntax from the zen shortcodes plugin. As per the following image:  

![Logo Alternative](logo-html.png)

Disable this option so only the alternate logo is displayed!

![Logo Alternative](logo_html_permi.png)
Do not forget to create a module for the logo of the mobile version as the image. The other settings are the same as the previous one.

![Logo](logo_mobile.png)

Remember to select all the contents within the text field, and add the link under the picture.

![Logo](insert_link.png)


To view the list of Zen Shortcode tags, access path: Features menu> Tools > Zen Shortcode> tab font icons:

![Logo](zencode.jpg)

![Logo](font-icons.png)

To customize the logo, follow the panel according to the image:

![Logo](customize-logo.png)

## Social Icons

The social icons are located in the bottom position of the theme.

### SOCIAL POSITION BOTTOM
![Social Icons](social.png)

- The social icons position is within the bottom line, according to the image:

![Social Icons](social-position.png)


### Social icon content
The content for the social icons can be set in the social panel in the template panel.

![Social icon content](social-icons-settings.png)

### Social Icon appearance

The color, size and other aspects of the social icon appearance can be controlled via the general settings side panel in the template's design panel.

![Social icon content2](screen_social_admin.png)

![Social icon content2](social-icons-settings2.png)


### Social icons on smaller screens

Accessing the project in portable devices, social icons are like the image:

![Social icon Mobile](social-portable.png)


As can be seen in the screenshot above, the social block is designed to be hidden on all screens larger than the phone breakpoint size. The value for the breakpoints can be set in the Layout > Breakpoints section of the General settings side panel.


### Social Icon appearance

The colour, size and other aspects of the social-mobile icon appearance can be controlled via the general settings side panel in the template's design panel.

![Social Icons mobile](social-icons-mobile.png)


## Module Banner Slideshow

![slideshow](banner-top.png)


To configure the top slideshow, see the illustration below:

![slideshow](config-slideshow.gif) 


See the settings screens:

![slideshow](config_default-slideshow.png) 



Slideshow items use standard joomla articles:


![slideshow](content1-slideshow.png)

![slideshow](content2-slideshow.png)

The content selection is made according to the image:

![slideshow](select-content_slideshow.gif)


The image is automatically retrieved from the item currently set to display however if the image doesn't exist then the slideshow will display a blank tile which uses the primary color set in the Zentools2 theme panel.

![slideshow Setup](screen_content_banner1.png)

To use the Aussie slideshow style, you need to add a class suffix in the modules advanced settings tab equal to the following:

     aussie-slideshow wave-border


![slideshow](class-slideshow.png) 


## Module OUR SERVICES | THE HOSPITAL


![our services ](screen_module_especi.png)


The module configuration in accordance with the image:

![our services ](screen_config_module_our.jpg)
- Please note the number of columns! (3)
- Note the use of "||" to separate the module caption title.
- This is the thin module in position grid1.
- Leave module title display enabled

For setting the module items, follow the picture:

![our services ](screen_config_our.gif) 
The content settings are according to the image:

![our services ](screen_content_our.gif) 


The content that is displayed is generated from joomla articles.
For the item's icon, use the zen shortcodes plugin.

![our services ](screen_content_our.png)

For the module to use the Utafiti style, the module class suffix and header class should be as follows (Including preceding spaces), as well as the module style and the head tag select options:

Module class suffix: 

     zen-grid-icons

Header class:

    zen-center zen-line

![our services ](screen_sufix_our.png)


## Module THE HOSPITAL | KNOW MORE ABOUT US

![the hospital](screen_the_hospital.png)

The module configuration follows the image:

![the hospital](screen_module_the_hospital.gif)

- Note the use of "||" to separate the module caption title.
- This is the thin module in position grid5.
- Leave module title display enabled


For setting the module items, follow the picture:

![the hospital](screen_module_the_hospital-1.gif)


The content settings are according to the image:

![the hospital](screen_module_the_hospital-2.gif)


The content, text, title and image. that are displayed are generated from joomla articles.

![the hospital](screen_content_the_hospital.png)
![the hospital](screen_img_the_hospital.png)


For the module to use the Utafiti style, the module class suffix and header class should be as follows (Including preceding spaces), as well as the module style and the head tag select options:

Module class suffix: 

     utafiti-know-more

Header class:

    zen-center zen-line


![our services ](screen_hospital_sufx.png)


## Module OUR TEAM

![our team](screen_profi.png)


The module configuration follows the image:

![our team](screen_team_1.png)

![our team](screen_team1.gif)


The content settings are according to the image:

![our team](screen_team2.gif)


To select more than one category in the 'CONTENT' tab, press CTRL (Windows) or Command (MAC).

For the module to use the Utafiti style, the module class suffix should be as follows (Including preceding space), as well as the module style and the head tag select options:

Module class suffix: 

     utafiti-our-team


![our team ](screen_team_3.png)


The content that is displayed is generated from joomla articles. 

![our team ](screen_team_4.png)
![our team ](screen_team_42.png)



## Module FROM THE BLOG | LATEST NEWS

![our services ](screen_blog.png)


The module configuration follows the image:
![our services ](screen_last.gif)

![our services ](screen_last_2.gif)


- Note the use of "||" to separate the module caption title.
- This is the thin module in position grid13.
- Leave module title display enabled


The content settings are according to the image:

![our services ](screen_last_3.gif)


For the module to use the Utafiti style, the module class suffix and header class should be as follows (Including preceding spaces), as well as the module style and the head tag select options:

Module class suffix: 

     utafiti-latest-news

Header class:

    zen-center zen-line

![our team ](screen-last.png)

The content that is displayed is generated from joomla articles. 

- CONTENT
![our team ](screen_last_2.png)

- IMAGES
![our team ](screen_last_3.png)

- DATE
![our team ](screen_last_4.png)


## Module TESTIMONY PATIENTS

![testimony](screen_testi.png)



The module configuration follows the image:
![our services ](screen_test.gif)

![our services ](screen_test_2.gif)


- Note the use of "||" to separate the module caption title.
- This is the thin module in position grid17.
- Leave module title display enabled

The content settings are according to the image:

![our services ](screen_test_3.gif)


For the module to use the Utafiti style, the module class suffix should be as follows (Including preceding space), as well as the module style select option:

Module class suffix: 

     utafiti-testimony

![our services ](screen_test_5.png)


The content that is displayed is generated from joomla articles.

![our services ](screen_test_6.png)

![our services ](screen_test_7.png)

# FOOTER

![our services ](screen_footer.png)


The bottom of the site is in accordance with the image.

Attention! For the maps module to work, do not forget to register your API in Google Maps.

# BREADCRUMB


The background used in the breadcrumb is managed by a zentools module. Where you can change the images,

![our services ](Screenshot-bread.png)


The settings you can see in the images:

![our services ](screen_config_bread.gif)
![our services ](screen_config_bread2.gif)