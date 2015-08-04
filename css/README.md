# Stylesheets
All CSS for your theme will be located here.

The `theme.css` file is the focal point for loading the styles. These could all have been in one file, but have been split up for the sake of more easily structuring and maintaining the codebase.

* **main.css** : main UI elements (wrapper for the main elfinder div, global styles, etc..)
* **icons.css** : icons across the UI (e.g. file associations)
* **toolbar.css** : toolbar at the top of the elfinder container. Contains toolbar buttons and searchbar
* **navbar.css** : directory navigation on the left-hand panel
* **view-list.css** : defines the list view
* **view-thumbnail.css** : defines the thumbnail/tile view
* **contextmenu.css** : context menu shown when right-clicking on in the list/thumbnail view or navbar
* **dialog.css** : information dialogs/modal windows
* **statusbar.css** : footer; contains information about directory and currently selected files

Note that many of the styles have a large degree of selectivity. E.g:

```css
.elfinder .elfinder-navbar .elfinder-navbar-dir.ui-state-active:hover { /* */ }
```

This is to minimize the need for using `!important` flags to override the existing styles (particularly with respect to jQuery UI's CSS).

## Tips
* Some styles have their `text-indent` property set to `-9999px` to keep the text out of view. If after styling you can't see the text (and you need to), change the text-indent property
* If you need to reset a style, the following normally suffices:

    ```css
      padding: 0;
      margin: 0;
      background: none;
      border: none;
    ```
