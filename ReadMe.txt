¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
ColourSpy
¯¯¯¯¯¯¯¯¯
Version 2.0
Monday, 10 November 2003
________________________________________________________________________

What?
¯¯¯¯¯
There are many people in the world that need to know exactly what that
colour is, right there under their mouse cursor. Thankfully, a plethora
of programs have been released, free and costly, that can do just that.

But those who own a copy of PowerPro need not install a piece of
software made for that purpose, because this functionality is available
through PowerPro, courtesy of the bar included in this package.

The ColourSpy bar will display the RGB and hex values of the colour
underneath the mouse cursor, as well as displaying the colour itself, so
that you know you have the right pixel. It will do this while the Ctrl
key is held down.

Once you have your desired colour, you can copy either the RGB or hex
values to the clipboard.
________________________________________________________________________

Requirements
¯¯¯¯¯¯¯¯¯¯¯¯
This bar uses a revised version of the Win plugin, which by default is
not included in installations of PowerPro v3.8 and under. You can find
the new version of this plugin at:

> http://www.windowspowerpro.com/download/win.zip

The ‘Use Quote for Escape in Expression Strings’ checkbox, found under
Setup > Advanced Setup > Characters, must be ticked for the script to
work. This option is not ticked by default.
________________________________________________________________________

Installation
¯¯¯¯¯¯¯¯¯¯¯¯
1. If you already have a copy of ColourSpy installed in your PowerPro
   configuration, then you may wish to remove:

   * the ColourSpy.txt file from your Scripts folder
   * the ColourSpy.icl file from your PowerPro folder

   as these files are no longer used.

2. Extract the contents of the archive into a temporary folder and
   double-click the Install script. PowerPro must be running in order
   to do this.

The installation script will attempt to detect the current configuration
and assume that you would like to install ColourSpy to this .PCF file,
but you have the option of selecting your own .PCF file during the
installation.
________________________________________________________________________

Usage
¯¯¯¯¯
The ColourSpy bar can be shown and hidden like any normal PowerPro bar,
through the use of *Bar Show, *Bar Hide, etc. commands. It can also be
set to ‘Auto Show as Bar’, should you wish.

Hold down the Ctrl key for the bar to capture colours.

Click on any numerical elements to copy those elements to the clipboard.

To move the ColourSpy bar to a new position on screen, hold down the
Ctrl key and drag. A later version will include the ability to drag the
title text, similar to standard windows.
________________________________________________________________________

To Conclude
¯¯¯¯¯¯¯¯¯¯¯
I'd really like to know if you need any help with this script, or if it
grows on you, so please feel free to Email me with any questions or
comments that you may have. My Email address can be found through the
PowerPro Yahoo! group, at:

> http://groups.yahoo.com/group/power-pro/

...or you can just leave a message at the Group -- there's a good chance
that I'll see it just as quickly.

Thanks to David Troesch for testing, and logical thought patterns, and
to Bruce for coming up with a great hex conversion script.

Best regards,
Alex Peters
________________________________________________________________________

Version History
¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
v2.0 (10/11/2003)
* Bar:
  * Complete visual redesign -- a skin is now used for greater control
    of element placement
  * Added the ability to copy individual RGB components to the clipboard
  * Multiple values copied to the clipboard are now only separated by
    spaces -- this will aid those who wish to create a script, for
    example, that processes the values on the clipboard
  * A script call is no longer required in order to successfully show
    and hide the bar -- the conventional *Bar Show, *Bar Hide, etc.
    commands now work
* Script:
  * Complete rewrite

v1.2 (22/8/2003)
* Bar:
  * Introduced mouse co-ordinates section
* Script:
  * Improved bar formatting code
* Documentation:
  * Added installation step for upgrading

v1.1 (22/8/2003)
* Bar import file:
  * Removed redundant lines
* Bar:
  * Removed right-click functionality of Close button
* Documentation:
  * Corrected typo

v1.0 (21/8/2003)
* Initial Release
________________________________________________________________________
