=======
hue-cli
=======

![Screenshot](https://raw.githubusercontent.com/rconradharris/hue-cli/master/screenshot.png)

Display light status::

    $ hue

    Office               ▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁   0%
    Bedroom              ▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁   0%
    Living Room          █████▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁   25%
    Kitchen              ▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁   0%

Turn on the lights::

    $ hue on bedroom office

Turn off the lights::

    $ hue off bedroom office

Dim the lights::

    $ hue dim office 10


Colorize a light::

    $ hue color office alice blue


Display available colors::

    $ hue colors


Get funky::

    $ hue funk office
