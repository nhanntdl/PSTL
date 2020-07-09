# PSTL
Project structure template layout

# Project files structure
    .
    ├── index.html                        # This file is the router, it will redirect to `your_config` page
    ├── screens                           # This folder contains all screen of your website
    |   ├── screen-name                   # This folder contains index.html file. The name foler is the directory on URL
    |   |   └── index.html                # This is index.html file, which contains all content of a single page 
    |   └── ...                           # This folder contains index.html file. The name foler is the directory on URL
    |       └── index.html                # This is index.html file, which contains all content of a single page
    ├── asset                             # This folder contains all asset of your website
    |   ├── fonts                         # This folder contains the fonts, which is used for website
    |   |   ├── font-file                 # This file is the config file of the font
    |   |   └── ...                       # This file is the config file of the font
    |   ├── images                        # This folder contains all images, which is used for website
    |   |   ├── screen-name               # This folder contains all images of a screen
    |   |   |   ├── image-name.png        # This file is a image of screen
    |   |   |   └── ...                   # This file is a image of screen
    |   |   └── ...                       # This folder contains all images of a screen
    |   ├── styles                        # This folder contains all stylesheet file of the website
    |   |   ├── modules                   # This folder contains all stylesheet file of modules
    |   |   |   ├── header.css
    |   |   |   ├── footer.css
    |   |   |   └── ...
    |   |   ├── style-name                # This folder contains all stylesheet file of a screen
    |   |   |   └── style-name.css
    |   |   ├── ...                       # This folder contains all stylesheet file of a screen
    |   |   |   └── ...
    |   |   └── style.css                 # This file contains stylesheet of common element in the website
    |   └── javascripts                   # This folder contains script of website
    |       ├── modules                   # This folder contains all script file of modules
    |       |   └── moduleName.js
    |       ├── screenName.js             # This file contains script of a screen
    |       └── index.js                  # This file contains script common
    ├── modules                           # This folder contains all module of website
    |   ├── common                        # This folder contains the common element
    |   |   └── index.html
    |   ├── module-name                   # This folder contains the `module-name` element
    |   |   └── index.html
    |   ├── header                        # This folder contains the header module
    |   |   └── index.html
    |   └── footer                        # This folder contains the footer module
    |       └── index.html
    └── README.md

# Editor and Plugin

## Live Server
* Install [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) to Quick Development Live Server with live browser reload.

## Formatting Rule
* Source code must be format by **[Prettier Code Formatter](https://prettier.io/)**
* [_How to use Prettier Code Formatter_](https://prettier.io/): Item `Editor Support`
* If you use `scss` to style, install plugin [Live Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass)
# HTML/CSS Style Guide
## Naming
* Use meaningful or generic ID and class names.
* Use `camel-case` style to naming for ID and class names.
* **NOTE:** If the ID or class will be use to handle the Javascript event, use `lowerCamelCase` style

# JS Style Guide
## Naming
* Use meaningful or generic ID and class names.
* Package names are all `lowerCamelCase`
* Class, interface, record, and typedef names are written in `UpperCamelCase`
* Method names are written in `lowerCamelCase`
* Constant names use `CONSTANT_CASE`
