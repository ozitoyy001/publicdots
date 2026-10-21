
# to install fastfetch 
 by the git :
 
https://github.com/fastfetch-cli/fastfetch

or

Ubuntu: ppa:zhangsongcui3371/fastfetch (Ubuntu 22.04 or newer; latest version)
Debian / Ubuntu: apt install fastfetch (Debian 13 or newer; Ubuntu 25.04 or newer)
Debian / Ubuntu: Download fastfetch-linux-<proper architecture>.deb from Github release page and double-click it (for Ubuntu 20.04 or newer and Debian 11 or newer).
Arch Linux: pacman -S fastfetch
Fedora: dnf install fastfetch
Gentoo: emerge --ask app-misc/fastfetch
Alpine: apk add --upgrade fastfetch
NixOS: nix-shell -p fastfetch

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
