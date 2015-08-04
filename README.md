# elFinder Theme Template
A pick-up-and-edit theme template for the [elFinder File Manager](https://github.com/Studio-42/elFinder).

# Aims
* To explain how to produce structured skins for elFinder
* To provide a base from which to quickly produce said skins
* Overcome skinning compatibility issues between elFinder versions (namely 2.0 to 2.x)

# Usage
All of elFinder's styling is done through CSS. There is an elaborate
collection of CSS classes designed to help change elFinder's aesthetics
to your likings, all of which are explained in the source code of the
template.

1. In the your elFinder installation, if a `themes` folder doesn't exist,
create one.
2. Create a folder in `themes` for your theme (e.g. `themes/[your-theme-name]`) and copy
the contents of this repository into it (or alternatively, clone this repository to the
`themes` directory and rename the folder to your liking).
3. Edit the template to fit your needs.
4. In your elFinder's html file (e.g. `elfinder.html`), load the
`themes/[your-theme-name]/css/theme.css` file after elFinder's base theme has loaded:

    ```html
    <!-- after all of the files in the /css/ directory are loaded -->
    <link rel="stylesheet" type="text/css" href="themes/[your-theme-name]/css/theme.css">
    ```
5. *(Optional)*  Load any extra Javascript from the `/themes/[your-theme-name]/js/`
directory after the files in `/js/` have loaded:

    ```html
    <!-- after all of the files in the /js/ directory are loaded -->
    <script type="text/javascript" src="themes/[your-theme-name]/js/yourscript.js"></script>
    ```

# Documentation
Check the source code and READMEs.
