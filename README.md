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
    |   ├── styles                        #
    |   |   ├── modules                   # gggg
    |   |   |   ├── header.css
    |   |   |   ├── footer.css
    |   |   |   └── ...
    |   |   ├── style-name
    |   |   |   └── style-name.css
    |   |   ├── ...
    |   |   |   └── ...
    |   |   └── style.css
    |   └── javascripts
    |       ├── modules
    |       |   └── moduleName.js
    |       ├── screenName.js
    |       └── index.js
    ├── modules
    |   ├── common
    |   |   └── index.html
    |   ├── module-name
    |   |   └── index.html
    |   ├── header
    |   |   └── index.html
    |   └── footer
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
