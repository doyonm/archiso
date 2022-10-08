# archiso based on releng (used to create the official monthly installation ISO)

## Packages

- alacritty
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

## I3 keybindings

- $mod + Enter  
  - Open Terminal (Alacritty)
- $mod + Shift + e        
  - Exit I3 (Return to lightdm)
- $mod + d        
  - DMenu
  
## Screen Resolution

  - Display mode
    - xrandr
  - Set resolution
    - xrandr --output NAME --mode 1440x900

## Account 

root (no password)
  
## Archiso
  
  sudo mkarchiso -v -w /tmp/archiso-tmp archlive
  -> out/archlinux-yyyy.mm.dd-x86_64.iso
  
  
