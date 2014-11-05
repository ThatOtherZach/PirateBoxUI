PirateBoxUI
===========

A new look for the PirateBox Project. Simply SSH into your box and copy this file over, replacing your current style.css file. 

A demo of the theme as it stands today can be seen here:
https://www.youtube.com/watch?v=gUDW2EKhOrQ

This is a work in progress, more themes might be available at a later date.


-- Themes (So far) --

Azure http://i.imgur.com/94goqsT.png
Carbon: http://i.imgur.com/r5Jl1cF.png
Pirates Smile: http://i.imgur.com/UcapyLO.png
Tree Hugger: http://i.imgur.com/xFyUXF6.png


-- Install Instructions --

1. Using SSH log into your PirateBox and navigate to your "www" folder.

2. Remove the current "style.css" file using this command:
	
	rm style.css

3. Check that the file has been deleted from the PirateBox. Then copy over the "style.css" from this folder using this command:

	scp root@b:/path/to/NEW-STYLE.CSS /path/to/WWW-FOLDER

3.1. Remember that "NEW-STYLE.CSS" is the style you just downloaded and "WWW-FOLDER" is where the old style.css was.

4. Once copied check the file is in place, then try to refresh or open the PirateBox on your browser, the new theme should now be in place.

5. Sit back and enjoy the view.
