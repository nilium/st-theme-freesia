Freesia Theme
==============================================================================

Freesia is a dark, fairly low-contrast theme with a lot of purple. It's intended for use with dark color schemes and currently only includes a dark variant.

![Freesia Theme](https://github.com/nilium/st-theme-freesia/raw/master/screenshot.png)

As of this writing, Freesia has only been tested in Sublime Text 3. You may attempt to use it in Sublime Text 2. If you encounter any bugs in ST2, please submit an issue or try to fix it yourself and submit a pull request. Either works.

This theme is built from the default Sublime theme, but is inspired by my previous theme, the [Nil theme](https://github.com/nilium/st2-nil-theme), and the [Flat UI theme by acondiff](https://github.com/acondiff/flatui-theme), both of which might suit you better if you find the color purple repulsive for some reason.


Installation
------------------------------------------------------------------------------

To install the theme, you'll need to first clone the theme's repository into your Sublime Text packages directory, like so:

    $ cd /path/to/sublime/Packages
    $ git clone git@github.com:nilium/st-theme-freesia.git 'Theme - Freesia'

Obviously replace the path with the correct one.

With the repository cloned, you can now hop into your preferences and set the `theme` key:

    {
        // other preferences above...
        "theme": "Freesia.sublime-theme"
    }

And you should be good to go.


Options
------------------------------------------------------------------------------

There are currently four options you should probably be aware of:

 - `highlight_modified_tabs` — If `true`, Freesia will highlight modified / dirty tabs. Otherwise, tabs have only two states: active and inactive. I recommend turning this on because it's handy.

- `freesia_large_tabs` and `freesia_small_tabs` — Only one of these should be set to true at a time. If both are set to true, small tabs win out. This simply changes the height of tabs and font size of tab labels. Does nothing special, but might be handy for people with lousy eyes and limited screen space, respectively.

- `freesia_soft_tab_marker` — If set to true, the colored status lines in tabs are blurred and softened a bit. It was kind of an accident originally, but it looked neat, so I made it optional.


Notes
------------------------------------------------------------------------------

The color scheme in the screenshot above is Big Duo, which is included with this theme and the Nil theme, just because it's what I use and it's easier to copy the theme directory than it is to figure out where I put it last. So, you get it too! You can probably select this from your preferences menu or whatever the equivalent is on your platform.

The font in the screenshot above is [PragmataPro](http://www.fsd.it/fonts/pragmatapro.htm) by Fabrizio Schiavi and it is awesome.


Thanks
------------------------------------------------------------------------------

A list of thanks to people who helped/contributed to Freesia's development, in no particular order:

- [FichteFoll](https://github.com/FichteFoll) for chatting about the design with me.
- Other peoples on ##sublimetext that chimed in.
- [acondiff](https://github.com/acondiff) for making the FlatUI theme.
