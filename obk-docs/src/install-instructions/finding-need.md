# Finding out what you need
### DISCLAIMER
*This chapter introduction is written with the intent that the user is new to the world of Linux, as such it introduces some basic concepts needed to determine what setup an user would need. If you already know what Distro (Ubuntu/Fedora etc) and DE (GNOME/KDE etc) you are using, then you can safely skip [To this section](#figuring-out-the-ims-you-need).*

## Identifying your Distro
There are countless linux-based distros in existence. However, the vast majority of them are based on one of the four major distros listed below :

- Debian GNU/Linux
- Ubuntu Linux
- Fedora Linux
- Arch Linux

Distros like Pop!_OS, Linux Mint and elementaryOS, for example, are based on Ubuntu Linux. Ubuntu Linux itself, in turn, is based on Debian Linux. Nobara Linux is a fork of Fedora Linux, Manjaro Linux is a fork of Arch Linux and EndeavourOS is based on Arch Linux.
To continue further, you must first correctly determine what your "base" distro is, as in, what major distro your distribution is based on. Such information can easily be found on the internet. 

*There are also independent distros like Void Linux, Gentoo Linux etc. But if you are using them, then chances are you are already experienced and knowledgeable enough in operating linux-based OSes, such that the install instructions are most likely redundant for you anyways, thus, such independent distros are considered out of scope for the install instructions section, although they still might get discussed in the Build Instructions section.*

## Identifying your Desktop Environment
There are also countless Desktop Environments (DEs) available for most linux-based distros, these are the Graphical Environments you actually interact with in your distros. The names of some widespread DEs are listed below :

- GNOME (Default DE in Debian GNU/Linux, Ubuntu Linux, Fedora Linux and RHEL/CentOS)
- KDE (Default DE in Manjaro Linux, OpenSUSE)
- Cinnamon (Default DE in Linux Mint)
- MATE
- Xfce

There are also some less widely used DEs which still have very strong followings :

- Budgie (The DE of now-defunct Solus)
- Pantheon (The DE of elementaryOS)
- Deepin DE (The DE of Deepin)

Note that most distros offer flavours or spins that let you use DEs other than the default one.
e.g. The Fedora KDE spin let's you use KDE on Fedora instead of GNOME.

## Figuring out the IMs you need
Most DEs prefer a specific IM, and usually ONE specific IM out of either iBus or fcitx. The install instructions will only cover the four major distros listed above, alongside as many DEs the community has created documentation for.

- The point of identifying your DE is to figure out which IM you should use.
- The point of identifying your distro is to guide you towards setting up those IMs for your specific distro.

Below is a table of various DEs and what IM they prefer.

| DE      |iBus     |fcitx    |
|---------|---------|---------|
|GNOME    | &check; | &cross; |
|KDE      | *&check;| &check; |
|Cinnamon | &check; | &check; |
|MATE     |         |         |
|Xfce     |         |         |
|Budgie   |         |         |
|Deepin DE|         |         |

**Note that you only need to configure ONE IM to use OpenBangla Keyboard. If your DE supports multiple IMs, you are free to choose either iBus or fcitx, but pick only one.**