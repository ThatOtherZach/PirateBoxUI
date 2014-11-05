PirateBoxUI
===========

A new look for the PirateBox Project. Simply SSH into your box and copy this file over, replacing your current style.css file. 

A demo of the theme as it stands today can be seen here:
https://www.youtube.com/watch?v=gUDW2EKhOrQ

This is a work in progress, more themes might be available at a later date.


<h5>Themes (So far)</h5>

Azure http://i.imgur.com/94goqsT.png<br>
Carbon: http://i.imgur.com/r5Jl1cF.png<br>
Pirates Smile: http://i.imgur.com/UcapyLO.png<br>
Tree Hugger: http://i.imgur.com/xFyUXF6.png<br>


<h5>Install Instructions</h5>

<ol>
<li>Using SSH, log into your PirateBox and navigate to your "www" folder.</li>
<li>Remove the current "style.css" file using the command:<br><code>rm style.css</code></li>
<li>Check that the file has been deleted from the PirateBox. Then copy over the "style.css" from this folder using the command:<br><code>scp root@b:/path/to/NEW-STYLE.CSS /path/to/WWW-FOLDER</code><br><br><i><b>Remember</b> that "NEW-STYLE.CSS" is the style you just downloaded and "WWW-FOLDER" is where the old style.css was.</i></li>
<li>Once copied check the file is in place, then try to refresh or open the PirateBox on your browser, the new theme should now be in place.</li>
<li>Sit back and enjoy the view.</li>
</ol>
