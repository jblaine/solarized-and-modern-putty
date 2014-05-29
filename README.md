Solarized Modern PuTTY Defaults
===============================

A Windows registry (.reg) file for setting the "Default Settings" PuTTY profile to [Solarized Dark PuTTY coloring](https://github.com/altercation/solarized) and most [modern sane PuTTY default settings](http://blog.sanctum.geek.nz/putty-configuration/) that most would want.

Usage TL;DR
===========
1. Download the `putty-modern-256color.reg`, review it in an editor, then double-click it.
2. Make new PuTTY profiles (they inherit the "Default Settings" profile)

Usage Detailed
==============
1. Read "What You Get" below to ensure this is what you want to set for your "Default Settings" profile in PuTTY.
2. OPTIONAL (most modern Linux distros have this): Test your intended destination systems for the putty-256color terminal definition by running ```infocmp putty-256color```. If you don't see a bunch of crazy terminal definition stuff spit to your screen, you don't have the putty-256color terminfo data. Figure out why and fix it if you care to continue.
3. OPTIONAL: Save your current PuTTY registry settings to a file with `regedit /ea putty-save.reg  HKEY_CURRENT_USER\Software\SimonTatham\PuTTY`
4. Download the `putty-modern-256color.reg` file from this git repository (review it in a text editor for your own security conscience)
5. Double-click on it to set the settings in the Windows registry, then use PuTTY to change anything you don't like.
6. Make new host-specific PuTTY profiles from within PuTTY (they will inherit your Default Settings).
7. If you get stuck in any way, go read the blog posts from Tom and Dag in the "Thanks" section of this README.

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

Thanks
======
* To Ethan Schoonover and those who have committed to the [Solarized](http://ethanschoonover.com/solarized) project
* To [Tom Ryder](http://blog.sanctum.geek.nz/putty-configuration/) and [Dag Wiiers](http://dag.wieers.com/blog/content/improving-putty-settings-on-windows) for their blog posts.
