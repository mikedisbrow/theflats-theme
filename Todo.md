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
