¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
ColourSpy
¯¯¯¯¯¯¯¯¯
Version 1.0
Thursday, 21 August 2003
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

Once you have your desired colour, you can copy either the RGB or hax
values to the clipboard.
________________________________________________________________________

Requirements
¯¯¯¯¯¯¯¯¯¯¯¯
This bar uses a revised version of the Win plugin, which by default is
not included in installations of PowerPro v3.8 and under. You can find
the new version of this plugin at:

> http://www.windowspowerpro.com/download/win.zip

The Events plugin (included with PowerPro) is used while the Ctrl key is
held down. This plugin is limited to 50 simultaneous events. So your
PowerPro configuration must use less than 50 simultaneous events. :-)
________________________________________________________________________

Installation
¯¯¯¯¯¯¯¯¯¯¯¯
1. Extract the ColourSpy.icl file into the folder where your PowerPro
   configuration (.PCF file) is located.
   (Usually ‘C:\Program Files\PowerPro’)

2. Extract the ColourSpy.txt file into your Scripts folder.
   (Usually ‘C:\Program Files\PowerPro\Scripts’)

3. Import the ColourSpyBar.txt file into your chosen PowerPro
   configuration.

4. Set up a method of showing the bar. The bar can be toggled using the
   PowerPro command ‘.ColourSpy@Toggle’.

The ColourSpy bar will not function if ‘Auto Show as Bar’ is ticked, or
if the bar is shown using e.g. ‘*Bar Show ColourSpy’. You must use the
command ‘.ColourSpy@Toggle’ for correct functionality.

You can emulate ‘Auto Show as Bar’ behaviour, if you wish, by adding a
startup entry on the Scheduler tab of PowerPro Configuration, for
‘.ColourSpy@Toggle’.
________________________________________________________________________

Usage
¯¯¯¯¯
To display the ColourSpy bar, use your selected method for executing the
command ‘.ColourSpy@Toggle’.

Hold down the Ctrl key for the bar to capture colours.

* The grip on the extreme left allows you to relocate the bar.
* The ‘X’ icon will close the bar.

* The ‘Copy’ icons will copy the values to the left of them, to the
  clipboard. These won't be visible until you have pressed Ctrl.
________________________________________________________________________

To Conclude
¯¯¯¯¯¯¯¯¯¯¯
Thanks to Bruce for coming up with a great hex conversion script -- the
bar wouldn't be able to show hex values otherwise!

I'd really like to know if any of my PowerPro work goes to use, so
please feel free to Email me with any questions or comments you may
have. You can reach me through the Yahoo! PowerPro group, at:

> http://groups.yahoo.com/group/power-pro/

Lastly, a special thanks to Bruce Switzer for PowerPro! :-)

Best regards,
Alex Peters
________________________________________________________________________

Version History
¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯
v1.0 (21/8/2003)
* Initial Release
________________________________________________________________________
