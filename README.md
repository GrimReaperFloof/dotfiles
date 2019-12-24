# My dotfiles
## Installation
Requirements:  
`stow`  
i3: `i3` `polybar` `dunst` `picom` `rofimoji` `flameshot`  
termite: `termite`  
zsh: `lf` `oh-my-zsh`  
pulseaudio: `pulseaudio` `jack2` `pulseaudio-jack`  
jackd.service: `systemd` `jack2`  

`stow i3` - sets up i3, polybar, dunst, and picom  
`stow termite` - sets up termite  
`stow zsh` - oh-my-zsh + lfcd keybind from Luke Smith (press Ctrl + O)  
`stow pulseaudio` - PulseAudio configuration for PulseAudio over JACK  
`stow jackd.service` - a jackd service you can use with systemd (user-based). Start with `systemctl start jackd --user`  

