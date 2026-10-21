
# to install fastfetch 
 by the git :
 
https://github.com/fastfetch-cli/fastfetch

or

Linux
Some distributions package outdated versions of fastfetch. Older versions receive no support, so please always try to use the latest version.

Packaging status
Ubuntu: ppa:zhangsongcui3371/fastfetch (Ubuntu 22.04 or newer; latest version)
Debian / Ubuntu: apt install fastfetch (Debian 13 or newer; Ubuntu 25.04 or newer)
Debian / Ubuntu: Download fastfetch-linux-<proper architecture>.deb from Github release page and double-click it (for Ubuntu 20.04 or newer and Debian 11 or newer).
Arch Linux: pacman -S fastfetch
Fedora: dnf install fastfetch
Gentoo: emerge --ask app-misc/fastfetch
Alpine: apk add --upgrade fastfetch
NixOS: nix-shell -p fastfetch
openSUSE: zypper install fastfetch
ALT Linux: apt-get install fastfetch
Exherbo: cave resolve --execute app-misc/fastfetch
Solus: eopkg install fastfetch
Slackware: sbopkg -i fastfetch
Void Linux: xbps-install fastfetch
Venom Linux: scratch install fastfetch
You may need sudo, doas, or sup to run these commands.

If fastfetch is not packaged for your distribution or an outdated version is packaged, linuxbrew is a good alternative: brew install fastfetch

macOS
Homebrew: brew install fastfetch
MacPorts: sudo port install fastfetch
Windows
scoop: scoop install fastfetch
Chocolatey: choco install fastfetch
winget: winget install fastfetch
MSYS2 MinGW: pacman -S mingw-w64-<subsystem>-<arch>-fastfetch
You may also download the program directly from the GitHub releases page in the form of an archive file.

BSD systems
FreeBSD: pkg install fastfetch
NetBSD: pkgin in fastfetch
OpenBSD: pkg_add fastfetch (Snapshots only)
DragonFly BSD: pkg install fastfetch (Snapshots only)
Android (Termux)
pkg install fastfetch

to customise your fastfetch you just need to change 

     ~/.config/fastfetch/config.jsonc
     

# logo 
 ```bash
     "logo": {
  "type": "file",
  "source": "/home/iso/fond/ascii-text.txt",
  "padding": { "top": 2, "left": 2 }
  }   
 },
```
