## The Flats

![image](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/Seafoam.png)

A dark, flat UI theme for Sublime Text 3. Uses Seafoam Green as the default accent color.  I just wanted a theme for myself that used aspects I liked in other themes, so I put them all together, made a bunch of changes, and this is the result.

***

### How to Install
##### Via Package Control
The easiest way to install is using [Sublime Package Control](https://packagecontrol.io), where The Flats is listed as `TheFlats Theme`.

1. Open Command Palette using menu item `Tools -> Command Palette...` or the shortcut `Command + Shift + P` on Mac
2. Type `Install`
3. Choose `Package Control: Install Package`
4. Search for `TheFlats` and hit `Enter`

##### Manual
You can also install the theme manually:

1. [Download the .zip](https://github.com/mikedisbrow/theflats-theme/archive/master.zip)
2. Unzip and rename the folder to `TheFlats Theme`
3. In the menu, go to `Sublime Text -> Preferences -> Browse Packages...` and copy the folder into the `Packages` directory. 
4. In the `misc` folder, you will find replacement app icons for Sublime Text, as well as a `fold.png` colored to match each UI accent color.  To use that color matched `fold.png` icon, copy it to `Packages/Theme - Default` to replace the default code folding icon in ST3.

##### Activate
Activate the UI theme and color scheme by modifying your user preferences file, which you can find using the menu item `Sublime Text -> Preferences -> Settings - User` and place

```js
  "color_scheme": "Packages/TheFlats Theme/schemes/The Flats.tmTheme",
  "theme": "TheFlats.sublime-theme",
```

***

### Settings & Options
##### General Settings
**Defaults**

* *Fonts*: 12pt  
* *Sidebar*: 8px, 4px
* *Tabs*: 34px

```js
  "flats_folder_icons": true,
  "flats_hide_icons": true,
  "flats_hide_tab_scroll_icons": true,
  "flats_sidebar_tree_small": true,			// 8px 2px
  "flats_sidebar_tree_large": true,			// 8px 6px	
  "flats_tabs_small": true,					    // 26px
  "flats_tabs_large": true,					    // 42px
  "flats_tabs_auto_width": true,
  "flats_sidebar_font_10": true,
  "flats_sidebar_font_11": true,
  "flats_sidebar_font_14": true,
  "flats_tabs_font_10": true,
  "flats_tabs_font_11": true,
  "flats_tabs_font_14": true,
```

##### UI Accent Colors
  * Seafoam - [Screenshot](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/Seafoam.png)
  * PreDawn - [Screenshot](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/Predawn.png)
  * Oceanic Next - [Screenshot](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/Oceanic.png)
  * Monokai - [Screenshot](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/Monokai.png)
  * Monokai Flat - [Screenshot](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/Monokai Flat.png)

```json
  "flats_ui_seafoam": true,
  "flats_ui_predawn": true,
  "flats_ui_oceanic": true,
  "flats_ui_monokai": true,
  "flats_ui_monokai_flat": true,
```
*I took Monokai Neue and softened some of the colors, because I can't look at that red forever. That's what* `monokai_flat` *is.*

##### Fonts
*Menlo, Monaco, and San Francisco are all included with OS X 10.10 and later*

- [Fira Code](https://github.com/tonsky/FiraCode "Fira Code - GitHub") @ GitHub (Free)
- [Hack](https://github.com/chrissimpkins/Hack "Hack - GitHub") @ GitHub (Free)
- The Font Bureau [Input](http://input.fontbureau.com "Font Bureau Input Fonts") (Free)
- Hoefler & Co. [Operator Mono](http://www.typography.com/fonts/operator/overview/ "Operator") ($)
- FSD [Pragmata Pro](http://www.fsd.it/shop/fonts/pragmatapro "Pragmata Pro") & [GitHub](https://github.com/fabrizioschiavi/pragmatapro "Pragmata Pro GitHub") ($)
- Adobe [Source Code Pro](https://github.com/adobe-fonts/source-code-pro) (Free)

```json
  "flats_font_fira": true,
  "flats_font_hack": true,
  "flats_font_inputsans": true,
  "flats_font_inputsansnarrow": true,
  "flats_font_menlo": true,
  "flats_font_monaco": true,
  "flats_font_operator_mono": true,
  "flats_font_pragmata": true,
  "flats_font_sanfrancisco": true,
  "flats_font_source_code_pro": true,
```

If you want to add support for fonts I have not included, go to your `Packages -> User` folder, create a folder `TheFlats Theme` and inside of it, create a file `TheFlats.sublime-theme` and paste in this code below and change the `X`s to the font family name you'd like to use. 

```json
[
    {   
       "class": "sidebar_label",
       "settings": ["flats_font_X"],
       "font.face": "X"
    },
    {
       "class": "tab_label",
       "settings": ["flats_font_X"],
       "font.face": "X"
    },
]
```

##### Folder Icons

![image](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/foldericons-rounded.png)

***
### Color Schemes
##### The Flats
*A dark theme, takes a lot from Oceanic Next and Material Dark. Fully supports HTML, CSS, JS, Markdown, GFM Markdown, JSON, SCSS, LESS, YAML, with Bracket Highlighter, Sublime Linter, GitGutter, and WordHighlight all defined. Ruby, PHP, and Python are WIP but more than sufficient as-is.*

![image](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/highlighting.png)

*I've also included the following color schemes, with a couple of small changes to background color, caret, bracket highlighter, gitgutter, etc.*

[Material Dark](https://github.com/equinusocio/material-theme), [Monokai Neue](https://github.com/josh-kaplan/sublime-monokai-neue), [Oceanic Next](https://github.com/voronianski/oceanic-next-color-scheme), and [PreDawn](https://github.com/jamiewilson/predawn)

***

### Replacement Icons for Sublime Text

*Made a few replacement icons for Sublime Text to go with the theme. Typical OS X style, using a few different fonts*

![image](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/app icons.png)

**Download** [here](https://dl.dropboxusercontent.com/u/3312456/app_icons.zip)

***

### Thanks
##### Themes & Color Schemes
[Spacegray](https://github.com/kkga/spacegray), [Material](https://github.com/equinusocio/material-theme), [PreDawn](https://github.com/jamiewilson/predawn), [Oceanic Next](https://github.com/voronianski/oceanic-next-color-scheme), [Monokai Neue](https://github.com/josh-kaplan/sublime-monokai-neue)

##### Icons
[Subway](https://github.com/mariuszostrowski/subway), [Iconic](https://github.com/iconic/open-iconic), [Ionicons](https://github.com/driftyco/ionicons/), [Octicons](https://octicons.github.com/), [Google Material Design](https://design.google.com/icons/)

##### Fonts
[CodeFace](https://github.com/chrissimpkins/codeface), [Hack](https://github.com/chrissimpkins/Hack), [Fira Code](https://github.com/tonsky/FiraCode), [Input Fonts](http://input.fontbureau.com)

***

### Known Issues
1. Depending on font, and font size, you may see descenders of letters slightly cut off in tabs.
