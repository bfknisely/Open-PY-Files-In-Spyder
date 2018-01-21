# Open-PY-Files-In-Spyder
# Created by Brian Knisely on January 21, 2018

When Spyder is installed through Anaconda3, .py files do not open with Spyder by default in Windows (10). 
The launch-spyder3.exe file will allow you to open .py files with Spyder by default once configured.
For transparency, the original .bat file used to create the .exe is included here. The .bat file would
also work for this method, but your .py files would no longer have any thumbnails.

First, download the launch-spyder3.exe file and place it in your Anaconda3 install folder.
Typically, this is C:\ProgramData\Anaconda3\
*Note, this is NOT the regular Program Files directory that many Windows programs install to.

Next, find a .py file on your computer. Right-click and select "Open with..." --> "Choose another app"

On the popup, click on "More apps", click the checkbox for "Always use this app to open .py files"
and then click on "Look for another app on this PC"

Navigate the file selector window to C:\ProgramData\Anaconda3\ and then click on the new "launch-spyder3.exe" file

That's it! Although Spyder is pretty slow to open, your files will now open in Spyder