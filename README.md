# SuperLanPlay_MacOSX
SuperLanPlay Client for Mac OSX

Installation Instructions.
==========================

Download SuperLanPlay.app.zip from this repository.

Drag it to your Desktop for example or Application Folder, as you want.

Do not extrac it even it is a zip. It just works as it is.

Open a Window Terminal and run this command before starting the SuperLanPlay for first time:

brew install libpcap libuv

If you see some errors because BREW is not installed in your Mac or you're getting errors try an installation from scratch writing these commands:

rm -rf /usr/local/Cellar /usr/local/.git && brew cleanup

ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install )"

And then finally run the same command as above:

brew install libpcap libuv

You just need to do this once.

Afterthat you're ready to launch SuperLanPlay.

Enjoy!!!
