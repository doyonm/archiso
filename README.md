# archiso based on releng (used to create the official monthly installation ISO)

## Additional packages

- alacritty
- dex
- dmenu
- firefox
- git
- gparted
- htop
- i3-gaps
- i3status
- lightdm
- lightdm-gtk-greeter
- mc
- networkmanager
- network-manager-applet
- xf86-video-qxl
- xf86-video-amdgpu
- xf86-video-intel
- xf86-video-nouveau
- xorg

## Account 

root (no password)

## I3 default keybindings

- Mod$ + Enter  Open Terminal (Alacritty)
- Mod$ + e        Exit I3 (Return to lightdm)
- Mod$ + d        DMenu
  
## Archiso
  
  sudo mkarchiso -v -w /tmp/archiso-tmp archlive
  -> out/archlinux-yyyy.mm.dd-x86_64.iso
  
  
