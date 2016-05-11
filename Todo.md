1. contrast mode
2. fix inactive tabs for contrast mode
```	#202020
	rgb(32,32,32)
	#232323
	rgb(35,35,35)
	#252525
	rgb(37,37,37)
	#2b2b2b
	rgb(43,43,43)
	#2d2d2d
	rgb(45,45,45)
	#303030
	rgb(48,48,48)
```
3. font face
``` json
    {
    "class": "tool_tip_label_control",
    "settings": ["theme_otto_global_custom_ui_font_face"],
    "font.face": "Sans-Serif"
    },
    {
    "class": "tool_tip_label_control",
    "settings": ["theme_otto_global_font_size_12"],
    "font.size": 12
    },
```
4. Tooltip Label Control
``` json
{
    "class": "tool_tip_control",
    "settings": ["theme_otto_accent_orange"],
    "layer0.tint": [241, 103, 60]
  },
```
5. Tab Label Selected Bold
``` json
{
    "class": "tab_label",
    "parents": [{"class": "tab_control", "attributes": ["selected"]}],
    "settings": ["theme_otto_tab_selected_label_bold"],
    "font.bold": true
  },
```
6. Status Bar Fonts
``` json
{
    "class": "label_control",
    "parents": [{"class": "status_bar"}],
    "settings": ["theme_otto_global_custom_ui_font_face"],
    "font.face": "Sans-Serif"
  },
  {
    "class": "label_control",
    "parents": [{"class": "status_bar"}],
    "settings": ["theme_otto_global_font_size_12"],
    "font.size": 12
  },
```
7. Sidebar Label Font Face
``` json
{
    "class": "sidebar_heading",
    "settings": ["theme_otto_global_custom_ui_font_face"],
    "font.face": "Sans-Serif"
  },
  
  {
    "class": "sidebar_label",
    "settings": ["theme_otto_global_custom_ui_font_face"],
    "font.face": "Sans-Serif"
  },
```
8.
``` json
{
    "class": "label_control",
    "settings": ["theme_otto_global_custom_ui_font_face"],
    "font.face": "Sans-Serif"
  },
  {
    "class": "button_control",
    "settings": ["theme_otto_global_font_size_14"],
    "min_size": [84, 0]
  },
```
# Code

```js
// ---------------------------
// CONTRAST OPTIONS
// ---------------------------
  {
       "class": "tabset_control",
       "settings": ["flats_contrast_darker"],
       "layer0.tint": [35,35,35],
  },
  {
       "class": "sidebar_container",
       "settings": ["flats_contrast_darker"],
       "layer0.tint": [35,35,35]
  },
  {
       "class": "tree_row",
       "settings": ["flats_contrast_darker"],
       "layer0.tint": [35,35,35]
  },
  {
       "class": "status_bar",
       "settings": ["flats_contrast_darker"],
       "layer0.tint": [35,35,35]
  },
  {
       "class": "scroll_corner_control",
       "settings": ["flats_contrast_darker"],
       "layer0.tint": [35,35,35]
    },    
    {
       "class": "scroll_bar_control",
       "settings": ["flats_contrast_darker"],
       "layer0.tint": [35,35,35]
    }, 
    {
       "class": "scroll_bar_control",
       "settings": ["flats_contrast_darker"],
       "attributes": ["horizontal"],
       "layer0.tint": [35,35,35]
    },
    {
       "class": "scroll_bar_control",
       "settings": ["overlay_scroll_bars", "flats_contrast_darker"],
       "layer0.tint": [35,35,35]
    },      
    {
       "class": "scroll_bar_control",
       "settings": ["overlay_scroll_bars", "flats_contrast_darker"],
       "attributes": ["horizontal"],
       "layer0.tint": [35,35,35]
    },
    {
       "class": "button_control",
       "settings": ["flats_contrast_darker"],
       "layer0.tint": [40, 40, 40]
    },
  // Hover button state
    {
       "class": "button_control",
       "settings": ["flats_contrast_darker"],
       "attributes": ["hover"],
       "layer0.tint": [45, 45, 45]
    },
  // Pressed button state
    {
       "class": "button_control",
       "settings": ["flats_contrast_darker"],
       "attributes": ["pressed"],
       "layer0.tint": [30, 30, 30]
    },
    {
       "class": "panel_control",
       "settings": ["flats_contrast_darker"],
       "layer0.tint": [35, 35, 35]
    },

  // LIGHTER

  {
       "class": "tabset_control",
       "settings": ["flats_contrast_lighter"],
       "layer0.tint": [45,45,45],
  },
  {
       "class": "sidebar_container",
       "settings": ["flats_contrast_lighter"],
       "layer0.tint": [45,45,45]
  },
  {
       "class": "tree_row",
       "settings": ["flats_contrast_lighter"],
       "layer0.tint": [45,45,45]
  },
  {
       "class": "status_bar",
       "settings": ["flats_contrast_lighter"],
       "layer0.tint": [45,45,45]
  },
  {
       "class": "scroll_corner_control",
       "settings": ["flats_contrast_lighter"],
       "layer0.tint": [45,45,45]
  },    
  {
       "class": "scroll_bar_control",
       "settings": ["flats_contrast_lighter"],
       "layer0.tint": [45,45,45]
  }, 
  {
       "class": "scroll_bar_control",
       "settings": ["flats_contrast_lighter"],
       "attributes": ["horizontal"],
       "layer0.tint": [45,45,45]
  },
  {
       "class": "scroll_bar_control",
       "settings": ["overlay_scroll_bars", "flats_contrast_lighter"],
       "layer0.tint": [45,45,45]
  },      
  {
       "class": "scroll_bar_control",
       "settings": ["overlay_scroll_bars", "flats_contrast_lighter"],
       "attributes": ["horizontal"],
       "layer0.tint": [45,45,45]
  },
  {
       "class": "button_control",
       "settings": ["flats_contrast_lighter"],
       "layer0.tint": [50, 50, 50]
    },
  // Hover button state
    {
       "class": "button_control",
       "settings": ["flats_contrast_lighter"],
       "attributes": ["hover"],
       "layer0.tint": [55, 55, 55]
    },
  // Pressed button state
    {
       "class": "button_control",
       "settings": ["flats_contrast_lighter"],
       "attributes": ["pressed"],
       "layer0.tint": [40, 40, 40]
    },
    {
       "class": "panel_control",
       "settings": ["flats_contrast_lighter"],
       "layer0.tint": [45, 45, 45]
    },
```

9. Tabs CONTRAST
 
  ``` json
    {
        "class": "tab_control",
        "content_margin": [24, 4, 20, 4],
        "max_margin_trim": 0,
        "hit_test_level": 0.5,
      
        "layer0.inner_margin": [24, 4],
        "layer0.opacity": 1.0,
      
        "layer1.inner_margin": [24, 4],
        "layer1.opacity": 0,
      
        "layer2.texture": "Theme - Otto/assets/global/commons/tabs/tab_selected.png",
        "layer2.inner_margin": [24, 4],
        "layer2.opacity": 0,
        "tint_index": 2,
      
        "layer3.texture": "Theme - Otto/assets/global/commons/tabs/tab_overlay.png",
        "layer3.inner_margin": [24, 4],
        "layer3.opacity": 0
      },
    ```
