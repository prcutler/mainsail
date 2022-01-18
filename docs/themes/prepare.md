---
layout: default
title: Prepare
parent: Theming
nav_order: 1
permalink: /theming/prepare
description: >-
  Create a basic folder structure to build your own theme.
---

# {{ page.title }}
{{ page.description }}

## .theme folder
A ".theme" folder will need to be created in your `config` folder.  
Please all files, such as CSS, in this folder to customize Mainsail.

The dot in the folder name means that it is a hidden folder. You wil need to activate "Show Hidden Files" in your operating system.
{: .info}

![screenshot](../assets/img/customizing/screenshot-display-hidden-files.png)

## Directory structure
The default file and folder structure is provided below. Please refer to the separate instructions for details.

All listed files in the .theme folder are optional and will only be loaded if they are provided.
{: .info}

```
+-- ..
|-- klipper_config
|   |-- .theme
|   |   |-- sidebar-logo.svg|jpg|png|gif
|   |   |-- sidebar-background.jpg|png|gif
|   |   |-- main-background.jpg|png|gif
|   |   |-- favicon-16x16.png
|   |   |-- favicon-32x32.png
|   |   |-- custom.css
|   |   |-- ...
```