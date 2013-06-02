Sublime-Text Setup
==================

A list of all my Sublime Text packages, preferences, and other stuff related to my editor setup.

![Sublime Text 2 screenshot](https://raw.github.com/jvrplmlmn/sublime-text/master/screenshot.png)

Theme
-----
* [Soda Dark](https://github.com/buymeasoda/soda-theme/)

Colour Scheme
-------------
* [Tomorrow Night Eighties](https://github.com/chriskempson/tomorrow-theme/blob/master/textmate/Tomorrow-Night-Eighties.tmTheme)

Font
----
* [Inconsolata](http://www.levien.com/type/myfonts/inconsolata.html)

Packages
--------

* [Package Control](http://wbond.net/sublime_packages/package_control) - Package Manager
* [SideBarEnhancements](https://github.com/titoBouzout/SideBarEnhancements) - Adds a lot of filesystem functionality to the sidebar
* [SublimeCodeIntel](https://github.com/Kronuz/SublimeCodeIntel) - Code Intelligence plugin
* [SublimeRope](https://github.com/JulianEberius/SublimeRope) - Adds Python completions and some IDE-like functions
* [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter) - Highlight syntax errors
* [Trailing Spaces](https://github.com/SublimeText/TrailingSpaces)

Preferences
-----------
```js
{
    // SUBLIME TEXT 2
    // User Preferences
    // https://github.com/jvrplmlmn/sublime-text

    // Theme, Colour Scheme, & Font
    "theme": "Soda Dark.sublime-theme",
    "color_scheme": "Packages/Color Scheme - Default/Tomorrow-Night-Eighties.tmTheme",
    "font_face": "Inconsolata",
    "font_size": 14.0,

    // Indentation
    "detect_indentation": false,
    "shift_tab_unindent": true,
    "translate_tabs_to_spaces": true,
    "tab_size": 4,
    "rulers": [80],

    // Encoding
    "fallback_encoding": "UTF-8",

    // Highlightning
    "highlight_line": true,
    "match_selection": true,

    // Gutter & line numbers
    "gutter": true,
    "margin": 0,
    "line_numbers": true,
    "fold_buttons": true,
    "fade_fold_buttons": false,

    // Side bar
    "show_folder_labels": true,
    "preview_on_click": true,
    "tree_animation_enabled": true,

    // Minimap
    "draw_minimap_border": true,

    // Tabs
    "show_tab_close_buttons": false,
    "highlight_modified_tabs": true,

    // Find
    "find_selected_text:": true,

    // Open
    "open_files_in_new_window": true,

    // Save
    "trim_trailing_white_space_on_save": true,
    "ensure_newline_at_eof_on_save": false,

    // Close
    "close_windows_when_empty": false,
    "hot_exit": false,
    "remember_open_files": false,

    // ---------------------------------------------------------------------
    // Misc
    // ---------------------------------------------------------------------
    // folder_exclude_patterns and file_exclude_patterns control which files
    // are listed in folders on the side bar. These can also be set on a per-
    // project basis.
    "folder_exclude_patterns": [".svn",
                                ".git",
                                ".hg",
                                "CVS"],
    "file_exclude_patterns": ["*.pyc",
                            "*.pyo",
                            "*.exe",
                            "*.dll",
                            "*.obj",
                            "*.o",
                            "*.a",
                            "*.lib",
                            "*.so",
                            "*.dylib",
                            "*.ncb",
                            "*.sdf",
                            "*.suo",
                            "*.pdb",
                            "*.idb",
                            ".DS_Store",
                            "*.class",
                            "*.psd",
                            "*.db"],

    // These files will still show up in the side bar, but won't be included in
    // Goto Anything or Find in Files
    "binary_file_patterns": ["*.jpg",
                            "*.jpeg",
                            "*.png",
                            "*.gif",
                            "*.ttf",
                            "*.tga",
                            "*.dds",
                            "*.ico",
                            "*.eot",
                            "*.pdf",
                            "*.swf",
                            "*.jar",
                            "*.zip"],

    // List any packages to ignore here. When removing entries from this list,
    // a restart may be required if the package contains plugins.
    "ignored_packages": ["Vintage"]
}
```
