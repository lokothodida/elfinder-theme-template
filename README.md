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

1. In the CSS directory of your elFinder installation, create a folder
for your theme, e.g.`/mytheme`.
2. Copy the contents of this repository into `mytheme`.
3. In your elFinder's html file (e.g. `elfinder.html`), load the `theme.css`
file from `mytheme` after elFinder's base theme has loaded:

```html
<!-- your theme -->
<link rel="stylesheet" type="text/css" href="css/mytheme/theme.css">
```

Check the source code for documentation.
