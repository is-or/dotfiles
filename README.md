# Configuration files:
**Clone the repo:**

`git clone 'https://github.com/is-or/df.git' $HOME/df`

**Copy the files to your `$HOME/.config` direcotry.**

`cd $HOME/df`

`cp -r */ $HOME/.config/`

`cp zshenv $HOME/.zshenv`

*(copy pacman-updates to $HOME/.local/bin)*

***Don't forget to make these files executable***

`chmod u+x $HOME/.config/bspwm/bspwmrc`

`chmod u+x $HOME/.config/polybar/launch.sh`

## Applications list:
*Here are the list of applications:*

`sudo pacman -Syu --no-confirm --needed bspwm sxhkd pamixer pulseaudio kitty zsh xcompmgr xwallpaper xorg gvfs gvfs-afc exa ttf-fira-code ttf-nerd-fonts-symbols xarchiver noto-fonts noto-fonts-emoji noto-fonts-cjk unzip materia-gtk-theme xorg-xbacklight mpv cmus xf86-video-intel dunst libnotify zathura zathura-pdf-mupdf rofi lxappearance pacman-contrib pcmanfm papirus-icon-theme chromium bat `

## Extras:
#### Shows feedback of entering password:
 `EDITOR=nvim visudo`

then add these:
 
 `Defaults	pwfeedback`  

#### Pacman config:
`sudo nvim /etc/pacman.conf`

then add these

`ParallelDownloads = 5`

`ILoveCandy`

#### AUR helper:
`git clone https://aur.archlinux.org/paru-bin $HOME/paru`

`cd $HOME/paru`

`makepkg -si`
