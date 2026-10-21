
# to install fastfetch 
 by the git :
 
https://github.com/fastfetch-cli/fastfetch

or

* Arch Linux: `pacman -S fastfetch`
* Fedora: `dnf install fastfetch`
* Gentoo: `emerge --ask app-misc/fastfetch`
* Alpine: `apk add --upgrade fastfetch`
* NixOS: `nix-shell -p fastfetch`
* openSUSE: `zypper install fastfetch`
* ALT Linux: `apt-get install fastfetch`
* Exherbo: `cave resolve --execute app-misc/fastfetch`
* Solus: `eopkg install fastfetch`
* Slackware: `sbopkg -i fastfetch`
* Void Linux: `xbps-install fastfetch`
* Venom Linux: `scratch install fastfetch`


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
