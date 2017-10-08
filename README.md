# sublime_text


this is my setting for customize sublime text 3.


How to use:

1. Install Package Control for Sublime Text 3:
   Link: https://packagecontrol.io/installation#st3


2. Close Sublime Text 3.


4. Put all this file to your oun Sublime Text 3 folder.


5. Open your Sublime text 3, and wait for download proccess.


6. Optional:

   I use Cmder for windows. So if you want to use it, please
   configure your terminal preference to:
   
   {
      
      "terminal": "C:\\cmder\\Cmder.exe",

      
      "parameters": ["/START", "%CWD%"],

      
      "env": {}
    
    }


7. Enjoy it.


All packages that will be installed are:


================================================================================

Package Control Messages
========================

GitGutter
---------

  Thanks for installing Git Gutter!!!
  
  ?? Follow me: @jisaacks
  
  
  ?? Git Gutter? Want to support development?
  
  I've teamed up with Wes Bos to offer the following discounts:
  
  +------------------------------------------------+
  |                                                |
  |   Use the coupon code GITGUTTER for $10 off    |
  |                                                |
  +------------------------------------------------+
  
  ?? ? ES6 ?
  
  ?? ES6.io/friend/GITGUTTER
  
  ?? ? Sublime Text Book ?
  
  ?? SublimeTextBook.com/friend/GITGUTTER
  
  ?? ? React For Beginners ?
  
  ?? ReactForBeginners.com/friend/GITGUTTER
  
  
  Join 15,000 other developers already learning with Wes Bos.
  
  These are fantastic resources - 100% money back guarantee! ??


SublimeLinter-csslint
---------------------

  SublimeLinter-csslint
  -------------------------------
  This linter plugin for SublimeLinter provides an interface to csslint.
  
  ** IMPORTANT! **
  
  Before this plugin will activate, you *must*
  follow the installation instructions here:
  
  https://github.com/SublimeLinter/SublimeLinter-csslint


Laravel Blade Highlighter
-------------------------

  Laravel Blade Highlighter
  
  This package adds syntax definitions for the Laravel 4 & 5 Blade engine.
  
  Works with Sublime Text 3.


SublimeLinter-php
-----------------

  SublimeLinter-php
  -------------------------------
  This linter plugin for SublimeLinter provides an interface to php -l.
  
  ** IMPORTANT! **
  
  Before this plugin will activate, you *must*
  follow the installation instructions here:
  
  https://github.com/SublimeLinter/SublimeLinter-php


Laravel 5 Snippets
------------------

  Laravel 5 Snippets for Sublime Text
  https://github.com/Lykegenes/laravel-5-snippets
  
  ********************************************************************************
  
  
  Thank you for installing this package!
  
  Please have a look at the project's Readme for up-to-date instructions.
  These snippets are consistent with the latest stable release of Laravel and its
  documentation, but some particularities are explained in the Readme file.
  
  The home page of the project can be found here :
  https://github.com/Lykegenes/laravel-5-snippets
  
  Improvements or suggestions? Contribute on GitHub!


EJS 2
-----

  Thanks for installing EJS 2 :)
  
  Here are some tips to help you get started with this package:
  
  
  ### Color Scheme
  
  EJS 2 comes with the "Dracula EJS" color scheme which you can select from:
  `Preferences` -> `Color Scheme` -> `EJS 2`.
  
  Oceanic Next (https://github.com/voronianski/oceanic-next-color-scheme) is also a
  good color scheme for EJS that works right out of the box.
  
  
  ### Setting the default syntax
  
  By default, files with the extension `.ejs` are opened with the `EJS (<% %>)` syntax.
  
  If you'd like to open files with a different extension as EJS or you want to use delimiters
  other than "<% %>", follow these steps to set the default EJS syntax for an extension:
  
  1. Open an EJS file
  2. Select `View` from the menu
  3. Then `Syntax` -> `Open all with current extension as...` -> `EJS 2` -> `EJS (<delimiter>)`
  4. Repeat this for each extension you want to open as EJS
  
  This package includes syntax definitions for the following additional delimiters: `<? ?>`, `<$ $>`, `<@ @>`.
  
  
  ### Snippets
  
  In the HTML scope:
  
  + `if`+`TAB` - Inserts EJS `if` statement
  + `for`+`TAB` - Inserts EJS `for` loop


Material Theme
--------------

  ## Material Theme for Sublime Text 3
  
  For more information on the Material Theme: https://github.com/equinusocio/material-theme
  
  **********************************************************************************************
  
  # Activate the theme
  
  You can active this theme from:
  - Command palette `Tools > Command Palette` (or <kbd>cmd/ctrl</kbd>+ <kbd>?</kbd>+<kbd>p</
  kbd>) by typing `Material Theme: Activate theme`. 
  - Context menu (Right click on the editor) and choose `Material Theme > Activate Material Theme`
  - `Preferences > Packages Settings` and choose `Material Theme > Activate Material Theme`
  
  You can also manually activate this theme by adding these lines to your user settings (**Preferences > Settings - User**):
  
  ```json
  "color_scheme": "Packages/Material Theme/schemes/Material-Theme.tmTheme",
  "theme": "Material-Theme.sublime-theme",
  ```
  
  ## File icons
  To enable file type icons you have to install an additional package, search for `zz File Icons` on Package Control, after install restart Sublime Text.
  
  **********************************************************************************************
  
  ### Other available theme options:
  
  ```
  "material_theme_accent_acid-lime"         : true , // Set acid-lime accent color
  "material_theme_accent_blue"              : true , // Set blue accent color
  "material_theme_accent_brba"              : true , // Set Breaking Bad green accent color
  "material_theme_accent_bright-teal"       : true , // Set bright-teal accent color
  "material_theme_accent_cyan"              : true , // Set cyan accent color
  "material_theme_accent_graphite"          : true , // Set graphite accent color
  "material_theme_accent_indigo"            : true , // Set indigo accent color
  "material_theme_accent_lime"              : true , // Set lime green accent color
  "material_theme_accent_orange"            : true , // Set orange accent color
  "material_theme_accent_pink"              : true , // Set pink accent color
  "material_theme_accent_purple"            : true , // Set purple accent color
  "material_theme_accent_red"               : true , // Set pale red accent color
  "material_theme_accent_sky"               : true , // Set bright-cyan accent color
  "material_theme_accent_tomato"            : true , // Set tomato red accent color
  "material_theme_accent_yellow"            : true , // Set yellow accent color
  "material_theme_bold_tab"                 : true , // Make the tab labels bolder
  "material_theme_compact_panel"            : true , // Set minimal padding for the search panel
  "material_theme_compact_sidebar"          : true , // Set compact side bar
  "material_theme_contrast_mode"            : true , // Enable sidebar and panels contrast mode
  "material_theme_disable_fileicons"        : true , // Hide sidebar file type icons
  "material_theme_arrow_folders"            : true , // Replace folder icons with arrows
  "material_theme_big_fileicons"            : true , // Show bigger file type icons
  "material_theme_disable_folder_animation" : true , // Disable folder animation
  "material_theme_disable_tree_indicator"   : true , // Disable sidebar file indicator
  "material_theme_bullet_tree_indicator"    : true , // Set a bullet as active tree indicator
  "material_theme_panel_separator"          : true , // Show bottom panel separator
  "material_theme_small_statusbar"          : true , // Set small status bar
  "material_theme_small_tab"                : true , // Set small tabs
  "material_theme_bright_scrollbars"        : true , // Bright scrollbars puck color
  "material_theme_accent_scrollbars"        : true , // Enable accent color for scrollbars
  "material_theme_tabs_autowidth"           : true , // Enable autowidth for tabs
  "material_theme_tabs_separator"           : true , // Show tabs separator, this disables tab hover 
  
  // If you use Material Theme - Appbar addon you can use additional settings:
  "material_theme_tree_headings"            : true , // Show sidebar headings
  ```
  
  **********************************************************************************************
  
  ### Recommended UI and font settings for a better experience:
  
  ```
  {
    "overlay_scroll_bars": "enabled",
    "line_padding_top": 3,
    "line_padding_bottom": 3,
    "always_show_minimap_viewport": true,
    "bold_folder_labels": true,
    "indent_guide_options": [ "draw_normal", "draw_active" ],   // Highlight active indent
    "font_options": [ "gray_antialias" ],                       // For retina Mac
  }
  ```


BracketHighlighter
------------------

  # BracketHighlighter
  
  Welcome to BracketHighlighter!  For a quick start guide, please go to  
  `Preferences->Package Settings->BracketHighlighter->Quick Start Guide`.


SublimeLinter-jshint
--------------------

  SublimeLinter-jshint
  -------------------------------
  This linter plugin for SublimeLinter provides an interface to jshint.
  
  ** IMPORTANT! **
  
  Before this plugin will activate, you *must*
  follow the installation instructions here:
  
  https://github.com/SublimeLinter/SublimeLinter-jshint


Emmet
-----

  Thank you for installing Emmet -- a toolkit that can greatly improve your workflow. Note that this plugin automatically downloads and installs PyV8 binary (see status bar message). 
  
  ******************************
  Please restart editor 
  to finish installation process 
  after PyV8 was downloaded.
  ******************************
  
  Tab key handler
  ==========================
  
  By default, Emmet allows you to expand abbreviations with Tab key in HTML, XML, HAML and CSS/SASS/LESS/Stylus documents. As a side effect, you can’t use some of your ST2 snippets.
  
  Please read https://github.com/sergeche/emmet-sublime#tab-key-handler about how Tab handler works and how to tweak its behavior to match your needs.
  
  Enter key
  ==========================
  
  In HTML and XML documents, Emmet overrides Enter key to insert formatted line breaks between opening and closing tags. In some cases it will break character input (for example, in Japanese language).
  
  To disable Enter key handler, simply add the following option in your user's Preferences file:
  
  "disable_formatted_linebreak": true
  
  Actions shortcuts
  ==========================
  
  Emmet has a number of actions with keyboard shortcuts that may override ones you're using commonly (for example, Ctrl-E or Ctrl-Down). Please read the project main page to get list of available actions and keyboard shortcuts and how to disable them:
  https://github.com/sergeche/emmet-sublime
  
  Documentation and examples:
  http://emmet.io
  
  ------------------------------
  Follow me on Twitter: @emmetio
  ------------------------------


SublimeLinter
-------------

  
    ____        _     _ _                _     _       _
   / ___| _   _| |__ | (_)_ __ ___   ___| |   (_)_ __ | |_ ___ _ __
   \___ \| | | | '_ \| | | '_ ` _ \ / _ \ |   | | '_ \| __/ _ \ '__|
    ___) | |_| | |_) | | | | | | | |  __/ |___| | | | | ||  __/ |
   |____/ \__,_|_.__/|_|_|_| |_| |_|\___|_____|_|_| |_|\__\___|_|
  
  
  Welcome to SublimeLinter, a linter framework for Sublime Text 3.
  
                   * * * IMPORTANT! * * *
  
          SublimeLinter 3 is NOT a drop-in replacement for
          earlier versions.
  
          Linters *NOT* included with SublimeLinter 3, 
          they must be installed separately.
  
          The settings are different.
  
                  * * * READ THE DOCS! * * *
  
  Otherwise you will never know how to install linters, nor will
  you know about all of the great new features in SublimeLinter 3.
  
  For complete documentation on how to install and use SublimeLinter,
  please see:
  
  http://www.sublimelinter.com
  
  
                   _   _      _       _
                  | | | | ___| |_ __ | |
                  | |_| |/ _ \ | '_ \| |
                  |  _  |  __/ | |_) |_|
                  |_| |_|\___|_| .__/(_)
                               |_|
  
  
  Hundreds of hours have been spent writing and documenting SublimeLinter
  to make it the best it can be — easy to use, easy to configure,
  easy to update, easy to extend. If you use SublimeLinter and feel
  it is making your coding life better and easier, please consider
  making a donation to help fund development and support.
  
  To donate: https://github.com/SublimeLinter/SublimeLinter3#share-the-love
  
  Thank you!


Color Highlighter
-----------------

  
  Color Highlighter v8.0 is released!
  
  For more info about the plugin visit https://github.com/Monnoroch/ColorHighlighter.
  
  Color Highlighter was developed for many years and features were added without consideration.
  As a result it has plenty of bugs and code is completely unmaintainable.
  Because of it, I've decided to rewrite the plugin from scratch using all the good programming practices I learned
  over the years.
  
  This is the first release of the new version and it might have some subtle bugs, especially on Windows and Mac, as I
  don't have machines with these systems. If you find any bugs, please file them in
  the bug tracker here: https://github.com/Monnoroch/ColorHighlighter/issues. I always appreciate your help and try to fix
  problems as soon as possible.
  
  The plugin is being developed by me alone in my spare time, so if you want to encourage me to build it
  better and faster, donations as always welcome.
  
  Thank you guys for your support, every little bit helps!


A File Icon
-----------

  ```
  
      $$$$$$\        $$$$$$$$\ $$\ $$\                 $$$$$$\                              
     $$  __$$\       $$  _____|\__|$$ |                \_$$  _|                             
     $$ /  $$ |      $$ |      $$\ $$ | $$$$$$\          $$ |  $$$$$$$\  $$$$$$\  $$$$$$$\  
     $$$$$$$$ |      $$$$$\    $$ |$$ |$$  __$$\         $$ | $$  _____|$$  __$$\ $$  __$$\ 
     $$  __$$ |      $$  __|   $$ |$$ |$$$$$$$$ |        $$ | $$ /      $$ /  $$ |$$ |  $$ |
     $$ |  $$ |      $$ |      $$ |$$ |$$   ____|        $$ | $$ |      $$ |  $$ |$$ |  $$ |
     $$ |  $$ |      $$ |      $$ |$$ |\$$$$$$$\       $$$$$$\\$$$$$$$\ \$$$$$$  |$$ |  $$ |
     \__|  \__|      \__|      \__|\__| \_______|      \______|\_______| \______/ \__|  \__|
  
  ```
  
  This package adds file specific icons to Sublime Text for improved visual grepping. 
  It's heavily inspired by Atom File Icons.
  
  ***
  
  1. Please restart Sublime Text for the applied icons to take effect.
  2. The icons for packages provided by the community require to be installed. 
     E.g. if you want to see SCSS icon you should install one of the SCSS syntax packages.
  
  ***
  
  I've put a lot of time and effort into making `A File Icon` awesome. If you love 
  it, you can [buy me a coffee](https://www.patreon.com/ihodev) ?.
