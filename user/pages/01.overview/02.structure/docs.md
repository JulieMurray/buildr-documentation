---
title: File structure
taxonomy:
    category: docs
---

The Build.r template uses the Zen Grid Framework v5. The Zen Grid Framework 5 is a template + Ajax plugin combination that is used to render and control the design and layout elements of your website.

## File structure

The file structure of a ZGFv5 based theme is typically as follow:

- component.php (standard Joomla component file)
- css (folder for all compiled less files and custom.css)
- error.php (standard error file)
- html (standard Joomla html override folder)
- images 
- js 
	- includes 
	- script.js (any template specific js)
	- template-default.js (Default compressed js file)
	- template-default.php (Default compressed gzip js file)
	- any generated template javascript files
- language
- less 
	- includes any template less files
	- where you place a custom.less file to include in the compiler
	- child folder - that can be used to load any less file into the less compiler when creating child themes. 
- offline.php (standard offline file)
- settings
	- includes
	- assets.xml (used by template to load required javascript in the compressor)
	- config/ stores the default and saved configuration files
	- layouts/ stores the default and saved layouts
	- settings.xml xml file used to populate the template admin in areas outside of the design panel
	- themer.xml used to populate settings in the design panel in the sidebar eg row styles etc
	- themer-exclude.json used to remove any items on a row by row basis in the design panel.
	- themes/ stores any saved themes
	- themes/presets store the theme presets that come with the theme
	- default-config.json - gets loaded if a config file does not exist
	- default-theme.json theme that is loaded if the theme does not exist
- templateInfo.php (used to populate content in the overview panel)
- template preview and template_thumbnail.png (template preview images)
- tpls
	- holds files that govern the layout
	- default.php the main layout container
	- blocks/ (sub layout files that are included by the parent)
- zengrid (holds the ZGF5 files)


Zen framework file structure
----
- admin (css, fonts and js for admin)
- config (main config file that renders the fields)
- fields (various displays for parameter types)
- helpers (ajax helpers for framework functionality)
- html Core framework html overrides for Joomla components
- libs (bootstrap, font awesome, zen less, mobile detect, less php, lessjs and more.)
- zen.php (the main zen class)
- zen.xml (holds release and version data)