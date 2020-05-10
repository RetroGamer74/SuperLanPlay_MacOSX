# SuperLanPlay_MacOSX

Get SuperLanPlay Client for Mac OSX from releases page and follow installation instructions.

![SuperLanClient_Mac_OSX](macosclient.jpg?raw=true "Title")

Installation Instructions.
==========================

Download SuperLanPlay app from [releases](releases) and extract it.

Drag it to your Desktop for example or Application Folder, as you want.

Open a Window Terminal and run this command before starting the SuperLanPlay for first time:

```
brew install libpcap libuv
```


If you see some errors because BREW is not installed in your Mac or you're getting errors try an installation from scratch writing these commands:


```
rm -rf /usr/local/Cellar /usr/local/.git && brew cleanup

ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install )"
```


And then finally run the same command as above:


```
brew install libpcap libuv
```


You just need to do this once.

Finally we're going to set a permission because usually it's needed.

Again in a terminal type the command:

```
whoami
```

The result of that command is your user name. We'll need it in the next command.

Type, now:

```
cd /dev

sudo chown your_username_here:admin bp*
```

for example if the user is retrogamer the command would be:

```
sudo chown retrogamer:admin bp*
```

Afterthat you're ready.

Remember the right procedure consist of three steps.

1. Launch browser and go to http://lanboard.retrogamer.tech. Get access until you see the page saying you can CONNECT.

2. Launch SuperLanPlay App and click CONNECT.

3. Finally connect the WiFi network in your Switch with the settings shown in the Settings page of the lanboard.

Repeat these steps each day you want to play because the Discord cookie expires from time to time.

Enjoy!!!

Video Help: https://youtu.be/yv3aX0WXsbg
