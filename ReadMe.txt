¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
ColourSpy
¯¯¯¯¯¯¯¯¯
Version 3.1
Tuesday, 5 October 2004
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
The script in this package uses features found only in PowerPro versions
v4.1 and above.
________________________________________________________________________

Installation
¯¯¯¯¯¯¯¯¯¯¯¯
1. If you already have a copy of ColourSpy v2.0 or earlier installed in
   your PowerPro configuration, then you will need to completely remove
   it since this version uses an entirely different approach.

   * Remove all references to the ColourSpy bar from your hotkeys and
     other bars.
   * Remove the ColourSpy command list from your configuration.
   * Delete the ColourSpy subfolder from your Skins folder.

2. Extract ColourSpy.PowerPro to your Scripts folder, e.g.:
   C:\Program Files\PowerPro\Scripts\ColourSpy.PowerPro

3. Create a folder named ColourSpy under your Skins folder, e.g.:
   C:\Program Files\PowerPro\Skins\ColourSpy

3. Extract Back.bmp and Skin.txt to this newly created folder, e.g.:
   C:\Program Files\PowerPro\Skins\ColourSpy\Back.bmp
   C:\Program Files\PowerPro\Skins\ColourSpy\Skin.txt

4. Optionally modify the BarPosSavePath variable to point to your
   desired location. This path will hold the position of the ColourSpy
   bar across PowerPro sessions.
________________________________________________________________________

Invoking
¯¯¯¯¯¯¯¯
Set up a hotkey or bar button to execute the following command, assuming
that you haven't renamed the script:

.ColourSpy

This will open the ColourSpy bar if it is not already open, or close it
otherwise.
________________________________________________________________________

Usage
¯¯¯¯¯
Hold down the Ctrl key for the bar to capture colours.

Click on any informational elements to copy those elements to the
clipboard.

To move the ColourSpy bar to a new position on screen, drag the title
text or the colour patch.
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
to Bruce for coming up with the foundation for a great hex conversion
script.

Best regards,
Alex Peters
________________________________________________________________________

Version History
¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
v3.1 (5/10/2004)
*  The script no longer conforms to Standard Configuration and should
   now function without modification on any PowerPro v4.1 configuration

v3.0 (10/7/2004)
*  Bar:
   *  The bar is no longer stored in the .PCF and so a script call is
      now required again to show and hide the bar -- *Bar Show, *Bar
      Hide, etc. commands will no longer work
   *  Clicking on empty information fields now results in an explanation
      message being displayed instead of an error
   *  Added the ability to drag the bar from the colour patch
*  Script:
   *  Complete rewrite
*  Documentation:
   *  Split Usage section into Invoking and Usage sections

v2.0 (10/11/2003)
*  Bar:
   *  Complete visual redesign -- a skin is now used for greater control
      of element placement
   *  Added the ability to copy individual RGB components to the
      clipboard
   *  Multiple values copied to the clipboard are now only separated by
      spaces -- this will aid those who wish to create a script, for
      example, that processes the values on the clipboard
   *  A script call is no longer required in order to successfully show
      and hide the bar -- the conventional *Bar Show, *Bar Hide, etc.
      commands now work
*  Script:
   *  Complete rewrite

v1.2 (22/8/2003)
*  Bar:
   *  Introduced mouse co-ordinates section
*  Script:
   *  Improved bar formatting code
*  Documentation:
   *  Added installation step for upgrading

v1.1 (22/8/2003)
*  Bar import file:
   *  Removed redundant lines
*  Bar:
   *  Removed right-click functionality of Close button
*  Documentation:
   *  Corrected typo

v1.0 (21/8/2003)
*  Initial release
________________________________________________________________________
