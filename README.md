# The Voidrice (Luke Smith <https://lukesmith.xyz>'s dotfiles)

These are the dotfiles deployed by [LARBS - LukeSmith](https://larbs.xyz) and as seen on
[Luke's YouTube channel](https://youtube.com/c/lukesmithxyz).

I only forked his Project and modified it by my needs ;)
THANK YOU LUKE!

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- vim/nvim (text editor)
	- zsh (shell)
	- sxhkd (general key binder)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- calcurse (calendar program)
	- tmux
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/files`
	- Directory bookmarks in `~/.config/directories`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

---------------
Luke's Dotfiles
---------------
- [dwm](https://github.com/lukesmithxyz/dwm) (window manager)
- [dwmblocks](https://github.com/lukesmithxyz/dwmblocks) (statusbar)
- [st](https://github.com/lukesmithxyz/st) (terminal emulator)

---------------
My Dotfiles
---------------
- [dwm](https://github.com/dschense/dwm) (window manager)
- [dwmblocks](https://github.com/dschense/dwmblocks) (statusbar)
- [st](https://github.com/dschense/st) (terminal emulator)

I also recommend trying out
[mutt-wizard](https://github.com/lukesmithxyz/mutt-wizard), which additionally
works with this setup. It gives you an easy-to-install terminal-based email
client regardless of your email provider. It is integrated into these dotfiles
as well.

## Install these dotfiles and all dependencies

This is the orginal way to install Lukes Dotfiles.
Use [LARBS](https://larbs.xyz) to autoinstall everything:


Get my modified verion:
```
curl -LO larbs.tr4sh.net/larbs.sh
```

orginal:
or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/LukeSmithxyz/LARBS/blob/master/progs.csv).

myfiles:
[dependencies](https://raw.githubusercontent.com/dschense/LARBS/master/progs.csv).