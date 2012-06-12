# Autumn

Autumn is a color scheme inspired by the colors you can find in the autumn.
Originally it was written as a color scheme for Komodo IDE but was ported to
Vim by Kenneth Love and Chris Jones. Since I moved to Vim I've made several
changes and improvements to the color scheme, however if it wasn't for Ken and
Chris I probably wouldn't have any clue where to start.

More information about the color scheme (as well as an up to date version) can
be found here: https://github.com/YorickPeterse/Autumn.vim

## Requirements

* Vim 7 or newer (7.3 or newer is recommended)
* A version of Vim capable of displaying lots of colors. Autumn was designed
  to be used in combination with Gvim, Macvim or similar implementations of
  Vim. However, Autumn does offer support for 256 color terminals but the
  colors will look slightly different.

## Installation

Assuming you've downloaded this file and placed it somewhere all you have to
do is move it into your "colordirectory:

    $ cp ~/Downloads/autumn.vim ~/.vim/colors/

## Supported Languages & Features

Autumn supports most, if not all features provided by Vim as well as a large
amount of programming/scripting languages such as Ruby and C. Autumn comes
with tweaked colors for the following languages:

* Ruby
* CSS
* HTML
* PHP
* Python
* Javascript

Other languages such as Java or more obscure ones such as Rust are also
supported. As long as there's a proper syntax highlighting plugin for the
language this color scheme should be able to handle it just fine. However, if
this isn't the case feel free to submit patches using Github.

Once installed you can activate it by running ``:color autumn`` in a Vim
session.

## License

Autumn.vim is licensed under the Creative Commons ShareAlike 3 license. Feel
free to modify and share it with others as long as you're nice enough to give
attribution.
