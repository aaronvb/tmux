<img width="1997" alt="Screen Shot 2020-10-09 at 3 02 26 PM" src="https://user-images.githubusercontent.com/100900/95642013-91c9b700-0a41-11eb-99fb-19ba1a74819e.png">

## Setup
Base config taken from https://github.com/simonsmith/dotfiles and https://github.com/fatih/dotfiles
Install tmux and required dependencies:
```
> brew install tmux
> brew install reattach-to-user-namespace
> brew install urlview
```

Clone repo into `~/.config`
```
> cd ~/.config
> git clone git@github.com:aaronvb/tmux.git
```

Link tmux conf
```
> cd ~/.config/tmux
> ln -s -f ~/.config/tmux/tmux.conf ~/.tmux.conf
```

Install tmux plugin manager https://github.com/tmux-plugins/tpm
```
> cd ~/.config/tmux
> git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm
```

Run tmux and install plugins
```
> tmux
<prefix> I (shift+i)
```
