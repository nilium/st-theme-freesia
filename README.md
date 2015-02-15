Freesia Theme
==============================================================================

Freesia is a dark, fairly low-contrast theme with a lot of purple. It's intended for use with dark to medium color schemes and currently includes dark, medium, and light variants.

![Freesia Theme](https://github.com/nilium/st-theme-freesia/raw/master/screenshot.png)

As of this writing, Freesia has only been tested in Sublime Text 3. You may attempt to use it in Sublime Text 2. If you encounter any bugs in ST2, please submit an issue or try to fix it yourself and submit a pull request. Either works.

This theme is built from the default Sublime theme, but is inspired by my previous theme, the [Nil theme](https://github.com/nilium/st2-nil-theme), and the [Flat UI theme by acondiff](https://github.com/acondiff/flatui-theme), both of which might suit you better if you find the color purple repulsive for some reason.

In addition, there are three other themes included in Freesia: Higuchi, Kano, and Void. Higuchi is a light theme while Kano is a medium-grey theme. Void, as the name suggests, is a very dark theme and mostly intended for working at night.

The Freesia theme's included color schemes are _Proxy_ (medium), _Big Duo_ (dark), _Triplet_ (dark), _Triplet Lite_ (medium-dark), _Kalopsia_ (dark), and _Kalopsia Darker_ (darker still). You can see screenshots of the color schemes themselves in the Color Schemes section below.


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


Void - Really Dark Theme
------------------------------------------------------------------------------

![Void Theme](https://github.com/nilium/st-theme-freesia/raw/master/screenshot-void.png)

Although not completely black, Void is fairly close. In a lot of ways, it's also the spiritual successor to the Nil theme, since it brings back the blue tab highlight as well.


Kano - Medium Theme
------------------------------------------------------------------------------

![Kano Theme](https://github.com/nilium/st-theme-freesia/raw/master/screenshot-kano.png)

The medium/middle-ground theme in Freesia is the Kano theme, which is mostly grey-ish blue, blue, and red. To use it, set your theme to `"Kano.sublime-theme"`.


Higuchi - Light Theme
------------------------------------------------------------------------------

![Higuchi Theme](https://github.com/nilium/st-theme-freesia/raw/master/screenshot-higuchi.png)

The light theme in the Freesia package is called Higuchi. To use it, just specify `"Higuchi.sublime-theme"` as your theme instead of Freesia in your settings.

Keep in mind that the colors might change a bit down the road.

The color scheme in the screenshot above is Sanakan, which is included in the Nil theme.


Options
------------------------------------------------------------------------------

There are currently a handful of options you should probably be aware of:

 - `highlight_modified_tabs` — If `true`, Freesia will highlight modified / dirty tabs. Otherwise, tabs have only two states: active and inactive. I recommend turning this on because it's handy.

- `freesia_large_tabs` and `freesia_small_tabs` — Only one of these should be set to true at a time. If both are set to true, small tabs win out. This simply changes the height of tabs and font size of tab labels. Does nothing special, but might be handy for people with lousy eyes and limited screen space, respectively.

    ![Tab Size Comparisons](https://github.com/nilium/st-theme-freesia/raw/master/screenshot-tabsizes.png)

- `freesia_soft_tab_marker` — If set to true, the colored status lines in tabs are blurred and softened a bit. It was kind of an accident originally, but it looked neat, so I made it optional.

    ![Soft Tabs Enabled](https://github.com/nilium/st-theme-freesia/raw/master/screenshot-softtabs.png)

- `freesia_borderless` — If true, removes the small border between the sidebar and content and between view groups.

- `freesia_small_vscroll` — If true, shrinks the vertical scrollbar so it's mostly only usable as an indicator of where you are. If you're like me and you navigate files by using find/go-to symbol/other tools, then this will get you back a tiny sliver of horizontal screen space. Who knows, maybe you'll have enough for three viewports horizontally?

- `freesia_medium_vscroll` and `freesia_medium_hscroll` — If true, the vertical and/or horizontal scrollbar will have a medium-sized puck, which is small but still grabbable. Handy for low-resolution screens.

- `freesia_large_hscroll` — And this is like the opposite of the last. It increases the size of the horizontal scrollbar to that of the default vertical scrollbar. In other words, if you find you need to click on the horizontal scrollbar, this option's for you and you can set it to true to get your big scrubby back.


Color Schemes
------------------------------------------------------------------------------

The following color schemes come with Freesia because they're my personal color schemes and therefore it's handy to have them all in the same package. If you want to use any of them, you can set the `color_scheme` key in your user settings file to `Packages/Theme - Freesia/<theme-name-here>.tmTheme`. The names and screenshots for each scheme are provided below.

#### Triplet

![Triplet Color Scheme](https://github.com/nilium/st-theme-freesia/raw/master/cs-screens/triplet.png)

A dark-ish color scheme and variant of Big Duo. Unlike Big Duo, it does not use background colors for entities and strings.

#### Triplet Lite

![Triplet Lite Color Scheme](https://github.com/nilium/st-theme-freesia/raw/master/cs-screens/triplet-lite.png)

A lighter variant of Triplet.

#### Proxy

![Proxy Color Scheme](https://github.com/nilium/st-theme-freesia/raw/master/cs-screens/proxy.png)

A medium grey-ish color scheme with a yellow-ish tint. Makes use of background colors when highlighting entities, like Big Duo.

#### Kalopsia

![Kalopsia Color Scheme](https://github.com/nilium/st-theme-freesia/raw/master/cs-screens/kalopsia.png)

A dark red and blue color scheme. Intended for use with the Void theme and night time coding.

#### Kalopsia Darker

![Kalopsia Darker Color Scheme](https://github.com/nilium/st-theme-freesia/raw/master/cs-screens/kalopsia-darker.png)

Same as Kalopsia, but slightly darker.

#### Big Duo

![Big Duo Color Scheme](https://github.com/nilium/st-theme-freesia/raw/master/cs-screens/big-duo.png)

A dark-ish color scheme that has a fair amount of pink, purple, and makes use of background colors to highlight various important structural elements, including entities, strings, and so on. Intended to make it easy to spot things when scrolling through source code.


Notes
------------------------------------------------------------------------------

The font in the screenshots above is [PragmataPro](http://www.fsd.it/fonts/pragmatapro.htm) by Fabrizio Schiavi and it is awesome.


Thanks
------------------------------------------------------------------------------

A list of thanks to people who helped/contributed to Freesia's development, in no particular order:

- [FichteFoll](https://github.com/FichteFoll) for chatting about the design with me.
- Other peoples on ##sublimetext that chimed in.
- [acondiff](https://github.com/acondiff) for making the FlatUI theme.
