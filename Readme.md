# fssrt
A Mac OS X Finder Sidebar Shortcut Repair Tool

![Finder sidebar shortcuts](https://raw.githubusercontent.com/brgmn/fssrt/master/documentation/images/finder-sidebar.png)

## I. About

Disapearing shortcuts to fileserver folders in Mac OS X is a daily pain. fssrt is just some applescript code and automator app that checks if the configured fileservers are reachable (via ping) and if yes, readds all shortcuts to a list of fileserver folders the finder sidebar. 

Read more about the mac os x sidebar shortcut problem here:
https://discussions.apple.com/thread/5556541

## II. Installation & Setup

1) Download newest version of fssrt from github

```
https://github.com/brgmn/fssrt
```
2) Copy the ffsrt folder to your Applications directory

3) Insert your network fileserver shares in shares.txt file

One share per line (protocol,ip,sharename) like this:

```
afp,192.168.1.4,myshare
```

4) Insert the shortcuts to fileserver folders you would like to see in the finder sidebar in config/shortcuts.txt

One shortcut per line (sharename,path) like this:

```
myshare,inbox/scan/today
myshare,team/marketing
```

5) Add fssrt to your finder menu (optional)

![Finder top menu integration](https://raw.githubusercontent.com/brgmn/fssrt/master/documentation/images/finder-menu.png)

You can just add the fssrt app by drag & dropping it to the finder top menubar holding cmd+alt pressed.

