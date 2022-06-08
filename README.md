# i3-gaps time saver
## Save time on post installation configuration of Arch Linux i3-gaps
### have a decent looking base ready to be build upon
```
mkdir ~/Downloads && cd ~/Downloads && git clone https://github.com/nrdrch/i3ts.git && cd i3ts && sudo chmod +x i3ts.sh
```
```
./i3ts.sh
```

# what the different options will do: 
## base: 
#### installs: 
polybar atom picom feh man-db alacritty btop neofetch base-devel fish rofi yay ly
#### sets: 
fish as your default shell 
#### sets:
ly as your log in screen
#### sets:
a decents wallpaper
#### configures: 
picom, i3, alacritty & polybar
## fsdeps: 
#### installs filesystem drivers:
ntfs-3g udisks2 btrfs-progs exfatprogs f2fs-tools dosfstools jfsutils cryptsetup lvm2 util-linux nilfs-utils xfsprogs
## more apps: 
#### installs: 
atom alacritty-themes didyoumean-bin bitwarden-git i3-swallow-git ksnip-git kvm
## fish alias:
#### sets:
various fish alias (see fishalias.sh)
#### notice:
some functions only work with firefox, atom & i3-swallow-git installed (mostly included in more apps
## grub config:)
#### installs:
os-prober
#### configures:
grub config with os prober enabled for those of you using multiple operating systems
## Quit:
#### exits the utility
