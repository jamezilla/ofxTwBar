Bridge to AntTweakBar - "a light and intuitive graphical user interface" - http://www.antisphere.com/Wiki/tools:anttweakbar

Note: this fork's API has one minor difference from smallfly's fork
which potentially breaks drop-in compatability. The main difference is
that the addButton() method has been renamed to addLabel() so an
actual addButton() could be implemented.

## Additions ##
* init() - overloaded method has more flexibility to take full [bar parameters syntax](http://www.antisphere.com/Wiki/tools:anttweakbar:twbarparamsyntax)
* addParam() - overloaded to support using variables that can only be accessed using getter and setter callbacks
* addButton() - can take a callback and object to fire a method

## Attrbibutions ##
Originally based on code from Cinder Lib.
Tested on MacOsx 10.6. Untested on Windows and Linux.
