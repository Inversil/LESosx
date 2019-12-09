# LESosx
This is the repository for the source code of the Live Enhancement Suite for Mac.

LES on mac is a modified version of the Hammerspoon client, which includes a bunch of custom scripts in it that self-extract.
If you go inside the .app package contents of the distributed release you'll already see all of the code and resources available to you.
When I work on LES I just edit the files inside of the app package contents.

This git is for looking around and potentially adding changes to the LES portion of the program; I won't be cloning hammerspoon here; but if people do something cool I'll definitely include it in the main dist.
This github repository only contains the modified files mimmicking the internal folder structure of the .app package.
The easter eggs and default configuration files are stored in the .Hidden directory.

I'm not sure if this is the best approach for this, so let me know if you want me to set this up differently.

The installer is a completely seperate program, that does nothing but downloading the .app from another git & whitelist the program from gatekeeper.

Feel free to message me on twitter or discord InvertedSilence#9999 if you want to talk to me about this git. 
Alternatively you can email me at yo@invertedsilence.com, but emails tend to not be as fast as text messages :-)
