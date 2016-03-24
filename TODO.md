# TODO

1. **New PNGs for panels for background color options**

2. 	Fix text bottom cut off in Tabs.
Content Margin?
Inner Margin?
Layer Margin?

3. 	make tab X bigger.  keep circle the same.

4. 	make sidebar X bigger with folder arrows

5. 	1px Border in Command Palette

6. 	Rounded scrollbars ?

7. 	Add more fonts to choices

8. 	See about changing the rest of the UI to different fonts

9. 	Progress Bar ? 
		
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

10. **Sidebar Icons need work**
> I managed to theme the folders too, with:

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
    	   "parents": {"class": "tree_row", "attributes": "expanded"]}],
    	   "layer0.texture": "User/Theme - Default/icons/folder_open.png",
    	 },

11. Icons .tmpreferences files to add more icons
> *How can I target* ```.erb``` *files so I can add a icon too them ? I tried* ```source.rails``` *and* ```text.html.rails``` *but it's not working.*
>
> If you want to add specific icons for specific file types you need to:
>
> 1. add the respective ```file_type_desired.png``` and ```file_type_desired@2x.png``` (for retina) in ```/package/Theme - Theme_Name/icons/``` folder (if ```Theme - Theme_Name``` folder does not exist create it yourself).
>
> 2. create a new ```Icon (new file type here).tmPreference``` file and put it in either ```/package/user/``` or ```/package/Theme - Theme_Name/``` folder.
>
> 3. in the newly created "Icon (new file type here)" file insert the following:

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
> For the scope of ```.erb``` files, it should be ```html.body.ruby```, but you can find it both by:
>
> 1. looking in the color scheme or language definition files to see which scopes are used for highlight.
>
> 2. add ```{ "keys": "ctrl+alt+shift+o"], "command": "show_scope_name" }``` to you user's keybindings, create a new ```.erb``` fyle and trigger the command to display current scope in the bottom status bar.

