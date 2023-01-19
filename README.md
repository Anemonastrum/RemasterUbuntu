## Linux Base 
- Ubuntu 22.04.1 Jammy [Link](http://releases.ubuntu.com/jammy/)

<img src=https://github.com/Anemonastrum/RemasterUbuntu/raw/main/Background/warty-final-ubuntu.png width="auto" height="auto"/>

## Sources
- GTK Theme [Source](https://github.com/vinceliuice/WhiteSur-gtk-theme)
- Icons Theme [Source](https://github.com/yeyushengfan258/Reversal-icon-theme)
- Cursors [Source](https://github.com/vinceliuice/Vimix-cursors)

## Features to Add
- New Fresh Shell Theme
- New Fresh Icon Theme
- New Fresh Cursor Theme
- Brand New Bootanimation
- Brand New Wallpapers
- Brand New Logo
- Snap Store Integrated

## Usage

!Internet Access is required to run the scripts!

UNPACK ISO

      ./unpack.sh
      
Chroot

      ./chroot.sh

Inside Chroot Environment

      mount -t proc none /proc
      mount -t sysfs none /sys
      mount -t devpts none /dev/pts 

      sudo apt update

      sudo apt install git

      git clone http://github.com/Anemonastrum/RemasterUbuntu/

      cd RemasterUbuntu

      sudo bash ./startremaster.sh
      
REPACK ISO

      ./repack.sh

## References

https://help.ubuntu.com/community/LiveCDCustomization