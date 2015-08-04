# elFinder Theme Template
A sketch and boilerplate of the CSS styles used to skin the [elFinder](https://github.com/Studio-42/elFinder) File Browser.

# Aims
* To explain how to make skins for elFinder
* To provide a base from which to quickly create skins
* Overcome skinning compatibility issues between elFinder versions (namely 2.0 to 2.1)

# Usage
All of elFinder's styling is done through CSS. There is an elaborate
collection of CSS classes designed to help change elFinder's aesthetics
to your likings, all of which are explained in the source code of the
template.

1. In the your elFinder installation, if a `themes` folder doesn't exist,
create one.
2. Create a folder in `themes` for your theme
3. Copy the contents of this repository into that new folder.
4. In your elFinder's html file (e.g. `elfinder.html`), load the
`themes/[your-theme-name]/css/theme.css` file after elFinder's base theme has loaded:

    ```html
    <!-- after all of the files in the /css/ directory are loaded -->
    <link rel="stylesheet" type="text/css" href="themes/mytheme/css/theme.css">
    ```
5. *(Optional)* : load any extra Javascript from the `/themes/[your-theme-name]/js/`
directory after the files in `/js/` have loaded:

    ```html
    <!-- after all of the files in the /js/ directory are loaded -->
    <script type="text/javascript" src="themes/mytheme/js/yourscript.js"></script>
    ```
# Documentation
Check the source code and READMEs.
