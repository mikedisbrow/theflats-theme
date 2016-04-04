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

```json
{
  "flats_folder_icons": true,				// Change ">" to folder icons
  "flats_hide_icons": true,					// Hide icons in sidebar
  "flats_hide_tab_scroll_icons": true,		// Hide "< >" and hamburger icon
  "flats_sidebar_tree_small": true,			// Reduce padding between lines
  "flats_sidebar_tree_large": true,			// Increase padding between lines
  "flats_tabs_small": true,					// 25px height
  "flats_tabs_large": true,					// 45px height
  "flats_tabs_auto_width": true,
  "flats_sidebar_font_10": true,			// Default font size is 12pt
  "flats_sidebar_font_11": true,
  "flats_sidebar_font_14": true,
  "flats_tabs_font_10": true,				// Default font size is 12pt
  "flats_tabs_font_11": true,
  "flats_tabs_font_14": true,

// Font Options in Tabs & Sidebar
  "flats_font_camingocode": true,			// Free
  "flats_font_fira": true,					// Free
  "flats_font_hack": true,					// Free
  "flats_font_inputsans": true,				// Free
  "flats_font_inputsansnarrow": true,		// Free
  "flats_font_operator": true,				// Paid
  "flats_font_pragmata": true,				// Paid
  "flats_font_menlo": true,					// System font on OS X
  "flats_font_monaco": true,				// System font on OS X
  "flats_font_sanfrancisco": true,			// System default on OS X
  
// UI Accent Colors
  "flats_ui_seafoam": true,					// Default
  "flats_ui_predawn": true,					// Orange & Yellow
  "flats_ui_oceanic": true,					// Yellow & Green
  "flats_ui_monokai": true,					// Red & Purple
}
```
* Fonts
	- [Camingo Code](https://www.myfonts.com/fonts/jan-fromm/camingo-code/ "MyFonts - Camingo Code") @ MyFonts
	- [Fira Code](https://github.com/tonsky/FiraCode "Fira Code - GitHub") @ GitHub
	- [Hack](https://github.com/chrissimpkins/Hack "Hack - GitHub") @ GitHub
	- The Font Bureau [Input](http://input.fontbureau.com "Font Bureau Input Fonts")
	- Hoefler & Co. [Operator ScreenSmart Pro](http://www.typography.com/fonts/operator/overview/ "Operator")
	- FSD [Pragmata Pro](http://www.fsd.it/shop/fonts/pragmatapro "Pragmata Pro") & [@ GitHub](https://github.com/fabrizioschiavi/pragmatapro "Pragmata Pro GitHub")

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

source.sublime-settings constant.language.boolean.jsongenericarrayelements, 
source.sublime-settings constant.numeric.jsongenericarrayelements
source.sublime-settings string.jsongenericarrayelements
source.sublime-settings constant.numeric.jsongenericarrayelements
source.sublime-settings keyword.other.name.sublime-settings

