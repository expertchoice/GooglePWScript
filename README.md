GooglePWScript
==============

Some notes from a fork author:

You have to have a little street smarts before running this, but the paucity of the instructions following mine are not helpful.  Here are some basic things you need to do to get started  

This script will change your password from its current state XXX to XXX1, XXX2, ..., XXX98, XXX99 and then to your "original" password.  It takes a few minutes to run.

Create a throwaway google account and practice on this first.  You can change the for-loop value from 99 to something small just to see the for loop is doing what it is supposed to do before you unleash it on your real account.


1.  Install [AutoIt](https://www.autoitscript.com/site/autoit/).  You may have to add the AutoIt directory to your environment path.
2.  You need to make sure that **.VBS** files are opened with **cscript.exe** instead of **wscript.exe**.  These executables are in the windows\system32 directory.
3.  Reset Chrome **entirely**.  Delete every profile, log out of every account, reset everything.  Heck, you might want to uninstall/reinstall chrome just to be safe.
4.  Close ALL your chrome browsers
5.  Now open up one chrome browser and login to your google account.  There should be only one account associated with this browser.  Close the browser (you still should be logged in)
6.  At a command prompt, go to your script directory and type **GooglePWReset.vbs > output.txt**
 

Google changes their login procedure from time to time, so this script will need to be adjusted accordingly.  It shouldn't be hard to do.

-----------------------------------------
A Script using the vbscript, autoIT com component, &amp; chrome to change your Google password 99 times.

99 times because Google has a 99 password history. So if you want to change your google password back to an old one - this is the answer.

Tip: Don't just doubleclick it to run it. CLose *everything*. Open a command prompt. THEN run it from the command prompt. 

That way, if it barfs, you can see what the password is set to.

Some SEO reasons why you want to use this to maybe help people find this:
Reset google password to old password
Use my old password on Google
Need to reset my google password back to old one I've used before.
