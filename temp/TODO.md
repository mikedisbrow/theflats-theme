# TODO

2. 	Fix text bottom cut off in Tabs.
Content Margin?
Inner Margin?
Layer Margin?

3.  Smooth out hover animations for
  *	 Find buttons
  *	 Command Palette
  *	 tabs
  *	 sidebar

8. 	See about changing the rest of the UI to different fonts

9. 	Progress Bar ? 
	```json		
	{
	    "class": "progress_bar_control",
	    "layer0.tint": [30, 30, 30],
	    "layer0.opacity": 1.0
	},
	{
	    "class": "progress_gauge_control",
	    "layer0.tint": [144, 144, 144],
	    "layer0.opacity": 1.0,
	    "content_margin": [0, 6]
	},
	```
10. **Sidebar Icons need work**
	* I managed to theme the folders too, with:

	```json
	// Sidebar folder closed
	{
	  "class": "icon_folder",
	  "layer0.texture": "User/Theme - Default/icons/folder.png",
	  "layer0.opacity": 1.0,
	  "content_margin": [8, 8]
	  },
	// Sidebar folder open
	{
	  "class": "icon_folder",
	  "parents": {
	  	"class": "tree_row", 
	  	"attributes": "expanded"
	  	},
	  "layer0.texture": "User/Theme - Default/icons/folder_open.png",
	},
	```
11. Icons .tmpreferences files to add more icons
	* *How can I target* ```.erb``` *files so I can add a icon too them ? I tried* ```source.rails``` *and* ```text.html.rails``` *but it's not working.*
		* If you want to add specific icons for specific file types you need to:
		1. add the respective ```file_type_desired.png``` and ```file_type_desired@2x.png``` (for retina) in ```/package/Theme - Theme_Name/icons/``` folder (if ```Theme - Theme_Name``` folder does not exist create it yourself).
		2. create a new ```Icon (new file type here).tmPreference``` file and put it in either ```/package/user/``` or ```/package/Theme - Theme_Name/``` folder.
		3. in the newly created "Icon (new file type here)" file insert the following:
		```xml
		<?xml version="1.0" encoding="UTF-8"?>
		<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs /PropertyList-1.0.dtd">
		<plist version="1.0">
		<dict>
		    <key>scope</key>
		    <string>%right scope for file type here%</string>
		    <key>settings</key>
		    <dict>
		        <key>icon</key>
		        <string>file_type_%new file type here%</string>
		    </dict>
		</dict>
		</plist>
		```
	4. For the scope of ```.erb``` files, it should be ```html.body.ruby```, but you can find it both by:
	  5. looking in the color scheme or language definition files to see which scopes are used for highlight.
	  6. add ```{ "keys": "ctrl+alt+shift+o"], "command": "show_scope_name" }``` to you user's keybindings, create a new ```.erb``` fyle and trigger the command to display current scope in the bottom status bar.



    {
        "class": "fold_button_control",
        "layer0.texture": "Theme - Spacegray/Spacegray/folder-closed.png",
        "layer0.tint": [167, 173, 186], // 04
        "layer0.opacity": 0.5,
        "layer0.inner_margin": 0,
        "content_margin": [8,8]
    },
    {
        "class": "fold_button_control",
        "attributes": ["hover"],
        "layer0.opacity": 1
    },
    {
        "class": "fold_button_control",
        "attributes": ["expanded"],
        "layer0.texture": "Theme - Spacegray/Spacegray/folder-open.png"
    },
    {
        "class": "fold_button_control",
        "attributes": ["expanded","hover"]
    },




{
        "class": "fold_button_control",
        "layer0.tint": [155, 242, 190],
        "layer0.opacity": 1.0
    },
    {
        "class": "fold_button_control",
        "attributes": ["hover"],
        "layer0.tint": [155, 242, 190],
        "layer0.opacity": 1.0
    },
    {
        "class": "fold_button_control",
        "attributes": ["expanded"],
        "layer0.tint": [117, 117, 117]
    },
    {
        "class": "fold_button_control",
        "attributes": ["expanded","hover"],
        "layer0.tint": [155, 242, 190],
    },
