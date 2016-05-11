1. contrast mode
2. fix inactive tabs for contrast mode
  ``` #202020
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
8. Label Control Font Face
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
11. Contrast mode code
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
10. Flats Monokai UI

  ``` json
    // ---------------------------------------------------
  // MONOKAI "settings": ["flats_ui_monokai"],
  // ---------------------------------------------------
    //   // ---------------------------
    //   // Tab Active Underlined
    //   // ---------------------------
    //     {
    //        "class": "tab_control",
    //        "settings": ["flats_ui_monokai"],
    //        "attributes": ["selected"],
    //        "layer0.texture": "TheFlats Theme/assets/monokai/tab_selected.png"
    //     },
    //   // ---------------------------
    //   // Tab Close Button Hover
    //   // ---------------------------
    //     {
    //        "class": "tab_close_button",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "tab_control"}],
    //        "attributes": ["hover"],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //   // ---------------------------
    //   // Tab Scroll Buttons Hover
    //   // ---------------------------
    //     {
    //        "class": "show_tabs_dropdown_button",
    //        "settings": ["flats_ui_monokai"],
    //        "attributes": ["hover"],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "scroll_tabs_left_button",
    //        "settings": ["flats_ui_monokai"],
    //        "attributes": ["hover"],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "scroll_tabs_right_button",
    //        "settings": ["flats_ui_monokai"],
    //        "attributes": ["hover"],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //   // ---------------------------
    //   // FOLD BUTTONS
    //   // ---------------------------
    //     {
    //        "class": "fold_button_control",
    //        "settings": ["flats_ui_monokai"],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "fold_button_control",
    //        "settings": ["flats_ui_monokai"],
    //        "attributes": ["hover"],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "fold_button_control",
    //        "settings": ["flats_ui_monokai"],
    //        "attributes": ["expanded"],
    //        "layer0.tint": [117, 117, 117]
    //     },
    //     {
    //        "class": "fold_button_control",
    //        "settings": ["flats_ui_monokai"],
    //        "attributes": ["expanded","hover"],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //   // ---------------------------
    //   // Scrollbars
    //   // ---------------------------
    //     {
    //        "class": "puck_control",
    //        "settings": ["flats_ui_monokai"],
    //        "layer0.texture": "TheFlats Theme/assets/monokai/puck_vertical.png"
    //     },
    //     {
    //        "class": "puck_control",
    //        "settings": ["flats_ui_monokai"],
    //        "attributes": ["horizontal"],
    //        "layer0.texture": "TheFlats Theme/assets/monokai/puck_horizontal.png"
    //     },
    //   // ---------------------------
    //   // Scrollbars Overlaid
    //   // ---------------------------
    //     {
    //        "class": "puck_control",
    //        "settings": ["overlay_scroll_bars", "flats_ui_monokai"],
    //        "layer0.texture": "TheFlats Theme/assets/monokai/puck_vertical_overlay.png"
    //     },
    //     {
    //        "class": "puck_control",
    //        "settings": ["overlay_scroll_bars", "flats_ui_monokai"],
    //        "attributes": ["horizontal"],
    //        "layer0.texture": "TheFlats Theme/assets/monokai/puck_horizontal_overlay.png"
    //     },
    //   // ---------------------------
    //   // PROGRESS BAR & DIALOG
    //   // ---------------------------
    //     {
    //        "class": "progress_gauge_control",
    //        "settings": ["flats_ui_monokai"],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //   // ---------------------------
    //   // Button labels
    //   // --------------------------- 
    //     {
    //        "class": "label_control",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "button_control"}],
    //        "color": [249, 38, 114]
    //     },
    //   // ---------------------------
    //   // Sidebar
    //   // ---------------------------
    //     {
    //        "class": "sidebar_label",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "tree_row","attributes": ["expanded"]}],
    //        "color": [249, 38, 114]
    //     },
    //     {
    //        "class": "close_button",
    //        "settings": ["flats_ui_monokai"],
    //        "attributes": ["hover"],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "disclosure_button_control",
    //        "attributes": ["expanded"],
    //        "settings": ["flats_ui_monokai"],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "disclosure_button_control",
    //        "settings": ["flats_folder_icons", "flats_ui_monokai"],
    //        "attributes": ["expanded"],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //   // ---------------------------
    //   // Quick Panel
    //   // ---------------------------
    //     {
    //        "class": "quick_panel_label",
    //        "settings": ["flats_ui_monokai"],
    //        "match_fg": [174, 129, 255, 255],
    //        "selected_match_fg": [249, 38, 114, 255]
    //     },
    //     {
    //        "class": "quick_panel_path_label",
    //        "settings": ["flats_ui_monokai"],
    //        "match_fg": [224, 224, 224, 255],
    //        "selected_match_fg": [174, 129, 255, 255]
    //     },
    //     {
    //        "class": "quick_panel_score_label",
    //        "settings": ["flats_ui_monokai"],
    //        "fg": [174, 129, 255, 255],
    //        "selected_fg": [249, 38, 114, 255]
    //     },
    //   // ---------------------------
    //   // Code Completion
    //   // ---------------------------
    //     {
    //        "class": "auto_complete_label",
    //        "settings": ["flats_ui_monokai"],
    //        "match_fg": [174, 129, 255, 255],
    //        "selected_match_fg": [249, 38, 114, 255]
    //     },
    //   // ---------------------------
    //   // Bottom Panel Buttons
    //   // ---------------------------
    //     {
    //        "class": "icon_regex",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "icon_button_control","attributes": ["selected"]}],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "icon_case",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "icon_button_control","attributes": ["selected"]}],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "icon_whole_word",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "icon_button_control","attributes": ["selected"]}],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "icon_context",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "icon_button_control","attributes": ["selected"]}],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "icon_use_buffer",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "icon_button_control","attributes": ["selected"]}],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "icon_reverse",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "icon_button_control","attributes": ["selected"]}],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "icon_wrap",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "icon_button_control","attributes": ["selected"]}],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "icon_in_selection",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "icon_button_control","attributes": ["selected"]}],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "icon_preserve_case",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "icon_button_control","attributes": ["selected"]}],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //     {
    //        "class": "icon_highlight",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "icon_button_control","attributes": ["selected"]}],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //   // ---------------------------
    //   // BOTTOM PANEL BUTTON
    //   // ---------------------------
    //     {
    //        "class": "panel_button_control",
    //        "settings": ["flats_ui_monokai"],
    //        "attributes": ["hover"],
    //        "layer0.tint": [249, 38, 114]
    //     },
    //   // ---------------------------
    //   // TEXT INPUT FIELD
    //   // ---------------------------
    //     {
    //        "class": "text_line_control",
    //        "settings": ["flats_ui_monokai"],
    //        "layer0.texture": "TheFlats Theme/assets/monokai/input_border.png"
    //     },
    //     {
    //        "class": "text_line_control",
    //        "settings": ["flats_ui_monokai"],
    //        "parents": [{"class": "overlay_control"}],
    //        "layer0.texture": "TheFlats Theme/assets/monokai/input_border_short.png"
    //     },
    //   // ------------------------------- 
    //   // TEXT INPUT MENU ICON
    //   // -------------------------------
    //     {
    //        "class": "dropdown_button_control",
    //        "settings": ["flats_ui_monokai"],
    //        "attributes": ["hover"],
    //        "layer1.tint": [249, 38, 114]
    //     },
  ```
