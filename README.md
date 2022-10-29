# archiso based on releng (used to create the official monthly installation ISO)

## Changes from releng

- Remove dhcpcd
- Remove broadcom-wl

## New packages

- alacritty
- broadcom-wl-dkms
- dmenu
- dkms
- firefox
- git
- gparted
- htop
- i3-gaps
- i3status
- lightdm
- lightdm-gtk-greeter
- linux-headers
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
- $mod + Shift + q        
  - Close active window
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
  
## Installation
  - sudo pacman -S archiso
  - sudo git clone https://github.com/doyonm/archiso/
  
## Create the iso 
  - sudo mkarchiso -v -w /tmp/archiso-tmp archiso 
  
  Will create iso in out directory :
  out/archlinux-yyyy.mm.dd-x86_64.iso
  
  
