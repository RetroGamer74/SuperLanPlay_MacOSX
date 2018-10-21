# SuperLanPlay_MacOSX
SuperLanPlay Client for Mac OSX

Installation Instructions.
==========================

Download SuperLanPlay.app.zip from this repository and extract it.

Drag it to your Desktop for example or Application Folder, as you want.

Open a Window Terminal and run this command before starting the SuperLanPlay for first time:

<b>brew install libpcap libuv</b>

If you see some errors because BREW is not installed in your Mac or you're getting errors try an installation from scratch writing these commands:

<b>rm -rf /usr/local/Cellar /usr/local/.git && brew cleanup</b>

<b>ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install )"</b>

And then finally run the same command as above:

<b>brew install libpcap libuv</b>

You just need to do this once.

Finally we're going to set a permission because usually it's needed.

Again in a terminal type the command:

<b>whoami</b>

The result of that command is your user name. We'll need it in the next command.

Type, now:

<b>cd /dev</b>

<b> sudo chown your_username_here:admin bp*</b>

for example if the user is retrogamer the command would be:

<b> sudo shown retrogamer:admin bp* </b>

Afterthat you're ready to launch SuperLanPlay.

Enjoy!!!

Video Help: https://youtu.be/yv3aX0WXsbg
