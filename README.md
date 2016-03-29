# The Flats

A dark, flat UI theme for Sublime Text 3. Uses Seafoam Green as the default accent color, popular on the hulls of saltwater fishing boats.

#### Screenshots

![image](Screenshots/theflats.png)
![image](Screenshots/theflats1.png)
![image](Screenshots/theflats2.png)
![image](Screenshots/theflats3.png)
![image](Screenshots/theflats4.png)

*The font used in the screenshots is [__Input Sans Narrow__](http://input.fontbureau.com).*

***

### How to Install

#### Via Package Control

The easiest way to install is using [Sublime Package Control](https://sublime.wbond.net), where The Flats is listed as `Theme - The_Flats`.

1. Open Command Palette using menu item `Tools -> Command Palette...` (<kbd>⇧</kbd><kbd>⌘</kbd><kbd>P</kbd> on Mac)
2. Choose `Package Control: Install Package`
3. Find `Theme - The_Flats` and hit <kbd>Enter</kbd>

#### Manual

You can also install the theme manually:

1. [Download the .zip](https://github.com/mikedisbrow/theflats/archive/master.zip)
2. Unzip and rename the folder to `Theme - The_Flats`
3. Copy the folder into `Packages` directory, which you can find using the menu item `Sublime Text -> Preferences -> Browse Packages...`
4. In `Theme - The_Flats/Misc/` you will find a replacement app icon for Sublime Text, as well as a `fold.png` colored to match each UI accent color.  To use that color matched `fold.png` icon, copy it to `Packages/Theme - Default` to replace the default code folding icon in ST3.
***

### How to Activate

Activate the UI theme and color scheme by modifying your user preferences file, which you can find using the menu item `Sublime Text -> Preferences -> Settings - User` (<kbd>⌘</kbd><kbd>,</kbd> on Mac).

***Note: Don't forget to restart Sublime Text after activating the theme.***

***

### Settings

##### Sidebar folder icons - [Screenshot](https://github.com/mikedisbrow/theflats/screenshots/theflats-folder-icons.jpg)
```json
  "flats_folder_icons": true,
```
##### Sidebar label font size
```json
  "flats_sidebar_font_10": true,
  "flats_sidebar_font_11": true,
  "flats_sidebar_font_14": true,
```
##### Sidebar tree row height
```json
  "flats_sidebar_tree_small": true,
  "flats_sidebar_tree_large": true,
```
##### Hide file icons
```json
  "flats_hide_icons": true,
```
##### Tab label font size
```json
  "flats_tabs_font_10": true,
  "flats_tabs_font_11": true,
  "flats_tabs_font_14": true,
```
##### Tab height
```json
  "flats_tabs_small": true,
```
```json
  "flats_tabs_large": true,
```
##### Tab width
```json
  "flats_tabs_auto_width": true,
```
##### Hide tab scroll icons
```json
  "flats_hide_tab_scroll_icons": true,
```
#### Font options in Sidebar and Tabs
_Obviously will only work if you have the fonts installed on your system.
Check [__CodeFace__](https://github.com/chrissimpkins/codeface "CodeFace") for a great bundle of monospaced fonts made for programming._

###### [Camingo Code - MyFonts](https://www.myfonts.com/fonts/jan-fromm/camingo-code/ "MyFonts - Camingo Code")
```json
  "flats_font_camingocode": true,
```
###### [Fira Code - GitHub](https://github.com/tonsky/FiraCode "Fira Code - GitHub")
```json
  "flats_font_fira": true,
```
###### [Hack - GitHub](https://github.com/chrissimpkins/Hack "Hack - GitHub")
```json
  "flats_font_hack": true,
```
###### [The Font Bureau - Input](http://input.fontbureau.com "Font Bureau Input Fonts")
```json
  "flats_font_inputsans": true,
  "flats_font_inputsansnarrow": true,
```
###### Menlo
_Installed on Macs as a system font_
```json
  "flats_font_menlo": true,
```
###### Monaco
_Installed on Macs as a system font_
```json
  "flats_font_monaco": true,
```
###### [Pragmata Pro](http://www.fsd.it/shop/fonts/pragmatapro "Pragmata Pro") & [GitHub](https://github.com/fabrizioschiavi/pragmatapro "Pragmata Pro GitHub")
```json
  "flats_font_pragmata": true,
```
###### San Francisco Text
_Default system font on OS X 10.10 Yosemite and 10.11 El Capitan_
```json
  "flats_font_sanfrancisco": true,
```
###### [Operator ScreenSmart Pro - Hoefler & Co.](http://www.typography.com/fonts/operator/overview/ "Operator")
```json
  "flats_font_operator": true,
```
#### Theme UI Accent colors
_Change colors to better coordinate with specific themes_
###### Seafoam - [Screenshot](http://github.com/mikedisbrow/theflats/screenshots/theflats-seafoam.jpg)
_Default color_
```json
  "flats_ui_seafoam": true,
```
###### PreDawn - [Screenshot](http://github.com/mikedisbrow/theflats/screenshots/theflats-predawn.jpg)
```json
  "flats_ui_predawn": true,
```
###### Oceanic Next - [Screenshot](http://github.com/mikedisbrow/theflats/screenshots/theflats-oceanic.jpg)
```json
  "flats_ui_oceanic": true,
```
###### One Dark - [Screenshot](http://github.com/mikedisbrow/theflats/screenshots/theflats-onedark.jpg)
```json
  "flats_ui_onedark": true,
```
###### Monokai - [Screenshot](http://github.com/mikedisbrow/theflats/screenshots/theflats-monokai.jpg)
```json
  "flats_ui_monokai": true,
```

***
### Color Schemes
##### The Flats Material
_Changed a few colors from the Material-Dark color scheme_

![image](screenshots/theflats.png)
![image](Screenshots/theflats1.png)
![image](Screenshots/theflats2.png)

##### The Flats for Markdown
_Example settings for Markdown_

Create a `Markdown.sublime-settings` file and place it in your `User` folder in `Sublime Text -> Preferences -> Browse Packages...`

```json
  {
  "word_wrap": true,
  "draw_indent_guides": false,
  "tab_size": 4,
  "translate_tabs_to_spaces": false,
  "trim_trailing_white_space_on_save": false,
  "gutter": true,
  "font_size": 14,
  "font_face": "Hack",
  "font_options":
  [
    "subpixel_antialias"
  ],
  "line_padding_bottom": 2,
  "line_padding_top": 2,
  "line_numbers": true,
  "spell_check": true,
  "color_scheme": "Packages/Predawn/predawn-gf-markdown.tmTheme",
  "draw_centered": true,
  "save_on_focus_lost": true,
  "caret_extra_bottom": 4,
  "caret_extra_top": 4,
  "caret_extra_width": 3,
  "caret_style": "phase",
  "wrap_width": 80
}
```
[Screenshot](http://github.com/mikedisbrow/theflats/screenshots/theflats-markdown.jpg)
***
### Thanks
##### Themes
[Spacegray Theme](https://github.com/kkga/spacegray) - Gadzhi Kharkharov

[Material Theme](https://github.com/equinusocio/material-theme) - Mattia Astorino

[PreDawn](https://github.com/jamiewilson/predawn) - Jamie Wilson

##### Color Schemes
[OneDark](https://github.com/IceTimux/one-dark-sublime-text-3-color-scheme) - Timothy de Jongh

[Oceanic Next](https://github.com/voronianski/oceanic-next-color-scheme) - Dmitri Voronianski

[Monokai Extended](https://github.com/jonschlinkert/sublime-monokai-extended) - Jon Schlinkert

##### Icons
[Subway Icons](https://github.com/mariuszostrowski/subway) - Mariusz Ostrowski

[Ionicons](https://github.com/driftyco/ionicons/)

[Octicons](https://octicons.github.com/)

[Font Awesome](https://fortawesome.github.io/Font-Awesome/icons/)

[Google Material Design](https://design.google.com/icons/)

[Iconic](https://github.com/iconic/open-iconic)

##### Fonts
[CodeFace](https://github.com/chrissimpkins/codeface) - Chris Simpkins

[Hack](https://github.com/chrissimpkins/Hack) - Chris Simpkins

[Fira Code](https://github.com/tonsky/FiraCode) - Nikita Prokopov

[Input Fonts](http://input.fontbureau.com) - The Font Bureau

[Camingo Code](https://www.myfonts.com/fonts/jan-fromm/camingo-code/) - Jan Fromm
