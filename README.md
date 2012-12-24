Solarized Modern PuTTY Defaults
===============================

A registry (.reg) file for setting [Solarized Dark PuTTY coloring][solarized] and most [modern sane PuTTY default settings][arabesque] that most would want.

Usage
=====
1. Read "What You Get" below to ensure this is what you want to set for your "Default Settings" profile in PuTTY.
2. Download the .reg file (review it in a text editor for your own security conscience)
3. Double-click on it to set the settings in the Windows registry, then use PuTTY to change anything you don't like.
4. Make new host-specific PuTTY profiles from within PuTTY (they will inherit your Default Settings).

What You Get
============
All of the following are applied to the standard "Default Settings" PuTTY profile. See Usage for more information on getting the settings applied to your existing profiles.

* Colors set to Solarized Dark
* Default terminal type: putty-256color
* Default scrollback buffer: 2000
* Remote character set: UTF-8
* Default font: Lucida Console, 12pt
* Window size: 80x40
* Font quality: ClearType
* Action of mouse buttons: "Compromise", Middle Extends Right Pastes
* Seconds between keepalives: 59
* SSH: version 2 only
* Hide mouse pointer when typing in window: On
* Unicode line-drawing code points: On
* X11 forwarding: On
* Close window on disconnect: Off
* Reset scrollback on key press: On
* Reset scrollback on display activity: Off

Contributing
============
All pull requests that address _common_ settings _most anyone_ would want will be strongly considered. If you simply disagree with the settings above, then just make your changes on your side.

[solarized]: https://github.com/altercation/solarized "Solarized - Precision colors for machines and people"
[arabesque]: http://blog.sanctum.geek.nz/putty-configuration/ "Tom Ryder (arabesque) - PuTTY Configuration"
