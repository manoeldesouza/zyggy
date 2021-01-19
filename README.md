# ZYGGY
## ZFS Administration GUI


Zyggy is a very simple GUI for basic ZFS administration. 
This is the GTK version of a previous development called 
ZC (ZFS commander) available in
https://github.com/manoeldesouza/zc

Commands available to date:
 - zfs create (Dataset)
 - zfs create -v (Volumes)
 - zfs rename
 - zfs snapshot
 - zfs clone
 - zfs promote
 - zfs remove
 - zfs get all
 - zpool rename
 - zpool remove
 - zpool get all


![zyggy](https://github.com/manoeldesouza/zyggy/blob/master/screenshot/zyggy.png)


## Dependencies

FreeBSD:
 - GTK3: pkg install python37 gtk3 py37-gobject3 (and xorg and a window manager of choice)


## Usage:

 sudo ./zyggy
