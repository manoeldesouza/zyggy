# ZYGGY
## ZFS Administration GUI


Zyggy is a very simple GUI for basic ZFS administration.
The system provides graphical access for most frequently 
used ZFS and ZPOOL commands, as listed below:

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


Zyggy is the GTK version of a previous development called 
ZC (ZFS commander) available in
https://github.com/manoeldesouza/zc


## Dependencies

 - FreeBSD: 
    - FreeBSD 12 release: pkg install python37 gtk3 py37-gobject3 (and xorg and a window manager of choice)
    - FreeBSD 13 current: pkg install python37 gtk3 py37-gobject3 (and xorg and a window manager of choice)
  
 - Manjaro: 
   - i3: pacman -S zfs
   
 - Ubuntu:
   - Dekstop 20.04: sudo apt install zfsutils-linux
   - Dekstop 20.10: sudo apt install zfsutils-linux
   - Server 20.10: sudo apt install zfsutils-linux python3.7-minimal libgtk-3-0 libgtk-3-dev libcairo-gobject2
   - Server 20.04: sudo apt install zfsutils-linux


## Usage:

 sudo ./zyggy
