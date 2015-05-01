# fssrt
A Mac OS X Finder Sidebar Shortcut Repair Tool

## I. Installation & Setup

1) Download newest version of fssrt from github

```
https://www.virtualbox.org/wiki/Downloads
```
2) Copy the ffsrt folder to your Applications directory

3) Insert your network fileserver shares in shares.txt file

One share per line (protocol,ip,sharename) like this:

```
afp,192.168.1.4,myshare
```

4) Insert the shortcuts to fileserver folders you would like to see in the finder sidebar in shortcuts.txt

One shortcut per line (sharename,path) like this:

```
myshare,inbox/scan/today
```

5) Add fssrt to your finder menu (optional)

You can just add the fssrt app by drag & dropping it to the finder top menubar while having cmd+alt pressed.
