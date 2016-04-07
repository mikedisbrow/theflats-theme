## The Flats

![image](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/Seafoam.png)

A dark, flat UI theme for Sublime Text 3. Uses Seafoam Green as the default accent color.  
I just wanted to make something I could be happy with staring at for long hours.  Inspired by [Predawn](https://github.com/jamiewilson/predawn), [Material Dark](https://github.com/equinusocio/material-theme), and [Spacegray](https://github.com/kkga/spacegray).

***

### How to Install
#### Via Package Control
The easiest way to install is using [Sublime Package Control](https://packagecontrol.io), where The Flats is listed as `TheFlats`.

1. Open Command Palette using menu item "*Tools -> Command Palette...*" or the shortcut *Command + Shift + P* on Mac
2. Type "*Install*"
3. Choose "*Package Control: Install Package*"
4. Search for "**TheFlats**" and hit *Enter*

#### Manual

You can also install the theme manually:

1. [Download the .zip](https://github.com/mikedisbrow/theflats-theme/archive/master.zip)
2. Unzip and rename the folder to "**TheFlats Theme**"
3. In the menu, go to "*Sublime Text -> Preferences -> Browse Packages...*" and copy the folder into the "*Packages*" directory. 
4. In the "*misc*" folder, you will find replacement app icons for Sublime Text, as well as a "*fold.png*" colored to match each UI accent color.  To use that color matched "*fold.png*" icon, copy it to "*Packages/Theme - Default*" to replace the default code folding icon in ST3.

***

### How to Activate

Activate the UI theme and color scheme by modifying your user preferences file, which you can find using the menu item "*Sublime Text -> Preferences -> Settings - User*".

***Note:*** *Don't forget to restart Sublime Text after activating the theme.*

***

### Settings & Options
#### General Settings
```js
{
  "flats_folder_icons": true,
  "flats_hide_icons": true,
  "flats_hide_tab_scroll_icons": true,
  "flats_sidebar_tree_small": true,
  "flats_sidebar_tree_large": true,
  "flats_tabs_small": true,
  "flats_tabs_large": true,
  "flats_tabs_auto_width": true,
  "flats_sidebar_font_10": true,
  "flats_sidebar_font_11": true,
  "flats_sidebar_font_14": true,
  "flats_tabs_font_10": true,
  "flats_tabs_font_11": true,
  "flats_tabs_font_14": true,
}
```
#### UI Accent Colors
  * Seafoam - [Screenshot](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/Seafoam.png)
  * PreDawn - [Screenshot](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/Predawn.png)
  * Oceanic Next - [Screenshot](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/Oceanic.png)
  * Monokai - [Screenshot](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/Monokai.png)
  * Monokai Flat - [Screenshot](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/Monokai Flat.png)

```js
{  
  // UI Accent Colors
  "flats_ui_seafoam": true,
  "flats_ui_predawn": true,
  "flats_ui_oceanic": true,
  "flats_ui_monokai": true,
  "flats_ui_monokai_flat": true,
}
```
#### Fonts
- [Camingo Code](https://www.myfonts.com/fonts/jan-fromm/camingo-code/ "MyFonts - Camingo Code") @ MyFonts
- [Fira Code](https://github.com/tonsky/FiraCode "Fira Code - GitHub") @ GitHub
- [Hack](https://github.com/chrissimpkins/Hack "Hack - GitHub") @ GitHub
- The Font Bureau [Input](http://input.fontbureau.com "Font Bureau Input Fonts")
- Hoefler & Co. [Operator ScreenSmart Pro](http://www.typography.com/fonts/operator/overview/ "Operator")
- FSD [Pragmata Pro](http://www.fsd.it/shop/fonts/pragmatapro "Pragmata Pro") & [@ GitHub](https://github.com/fabrizioschiavi/pragmatapro "Pragmata Pro GitHub")
```js
{
  // Font Options in Tabs & Sidebar
  "flats_font_camingocode": true,
  "flats_font_fira": true,
  "flats_font_hack": true,
  "flats_font_inputsans": true,
  "flats_font_inputsansnarrow": true,
  "flats_font_operator": true,
  "flats_font_pragmata": true,
  "flats_font_menlo": true,
  "flats_font_monaco": true,
  "flats_font_sanfrancisco": true,
}
```

*The font used in the screenshots is [__Input Sans Narrow__](http://input.fontbureau.com).*

***

### Folder Icons

![image](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/Folders.png)

***
### Color Schemes
##### Flats-Dark
*Adapted from Material-Dark and Oceanic Next*

##### Flats-GFM-Markdown


_Example settings for Markdown_

Create a `Markdown.sublime-settings` file and place it in your `User` folder in `Sublime Text -> Preferences -> Browse Packages...`

```js
{
  "word_wrap": true,
  "draw_indent_guides": false,
  "tab_size": 4,
  "translate_tabs_to_spaces": false,
  "trim_trailing_white_space_on_save": false,
  "gutter": true,
  "font_size": 15,
  "font_face": "Hack",
  "font_options":
  [
    "subpixel_antialias"
  ],
  "line_padding_bottom": 2,
  "line_padding_top": 2,
  "line_numbers": true,
  "spell_check": true,
  "color_scheme": "Packages/Flats/Flats-GFM-Markdown.tmTheme",
  "draw_centered": true,
  "save_on_focus_lost": true,
  "caret_extra_bottom": 4,
  "caret_extra_top": 4,
  "caret_extra_width": 3,
  "caret_style": "phase",
  "wrap_width": 80
}
```

##### Others
*I've also included the following color schemes, with a couple of small changes to carets, bracket highlighter, gitgutter, etc.*

*  Predawn
*  Predawn Markdown
*  Predawn GF Markdown
*  Material Dark
*  Oceanic Next
*  Monokai Neue Flat
  *  *Modified the colors slightly because regular Monokai just burns my retinas.*

***

### Replacement Icons for Sublime Text

*Made a few replacement icons for Sublime Text to go with the theme. Typical OS X style, using a few different fonts*

![image](https://raw.githubusercontent.com/mikedisbrow/theflats-theme/master/misc/screenshots/app%20icons.png)

***

### Thanks
*  **Themes & Color Schemes**	
    * [Spacegray Theme](https://github.com/kkga/spacegray) - Gadzhi Kharkharov
	* [Material Theme](https://github.com/equinusocio/material-theme) - Mattia Astorino
	* [PreDawn](https://github.com/jamiewilson/predawn) - Jamie Wilson
	* [Oceanic Next](https://github.com/voronianski/oceanic-next-color-scheme) - Dmitri Voronianski
	* [Monokai Neue](https://github.com/josh-kaplan/sublime-monokai-neue) - Josh Kaplan

*	**Icons**
	* [Subway Icons](https://github.com/mariuszostrowski/subway) - Mariusz Ostrowski
	* [Ionicons](https://github.com/driftyco/ionicons/)
	* [Octicons](https://octicons.github.com/)
	* [Font Awesome](https://fortawesome.github.io/Font-Awesome/icons/)
	* [Google Material Design](https://design.google.com/icons/)
	* [Iconic](https://github.com/iconic/open-iconic)

*	 **Fonts**
	* [CodeFace](https://github.com/chrissimpkins/codeface) - Chris Simpkins
	* [Hack](https://github.com/chrissimpkins/Hack) - Chris Simpkins
	* [Fira Code](https://github.com/tonsky/FiraCode) - Nikita Prokopov
	* [Input Fonts](http://input.fontbureau.com) - The Font Bureau
	* [Camingo Code](https://www.myfonts.com/fonts/jan-fromm/camingo-code/) - Jan Fromm
