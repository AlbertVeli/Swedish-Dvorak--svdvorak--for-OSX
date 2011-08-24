SwedishDvorak.keylayout for Mac OS X
====================================

![layout](https://github.com/AlbertVeli/Swedish-Dvorak--svdvorak--for-OSX/raw/master/svdvorak-osx.png "svdvorak OSX Layout")

This keyboard layout provides a Swedish Dvorak (svdvorak)
layout for OS X.

There are several Swedish Dvorak variants but, unlike in Norway, there
is no standard Swedish Dvorak layout and the community is fragmented.

The major difference between svdvorak and the svorak layout is
the placement of the Ö and Ä keys.

This layout has all major keys in the same place as the
Xorg svdvorak layout. The difference is that \, (), [] and {}
symbols are kept on the same places as on the standard Swedish
Apple layout (on the 7, 8 and 9 keys + shift and/or option key).


Installation
------------

* Copy SwedishDvorak.* to '/Library/Keyboard Layouts/':

  `cp SwedishDvorak.* '/Library/Keyboard Layouts/'`

* Restart the computer.

* Open System Preferences,
   go to Language & Text,
   then Input Sources, and
   tick Swedish Dvorak (svdvorak) in the list of input methods.

* Check "Show input menu in menu bar" to change keyboard layout
   from the menu bar.

* To use the keyboard layout on the login screen,
   open System Preferences, go to Accounts, then Login Options and
   select "Show input menu in login window".


Credits
-------

The NorwegianDvorak.keylayout was created by Vidar Bronken Gundersen:

 http://github.com/vibrog/no-dvorak-osx

I created this layout by opening the NorwegianDvorak.keylayout
file in Ukulele and switched places between the Swedish ö and ä
and the Norwegian/Danish ø and æ keys. Then some minor key adjustments
was made to make the layout closer to the svdvorak variant in Xorg (created
by Gunnar Parment).

Hopefully there will come a day when Scandinavian (specially Swedish)
Dvorak typers will agree on a common layout so it can be included in all
major operating systems. I chose to use the svdvorak variant because it
is the one most similar to the standardized Norwegian layout.

