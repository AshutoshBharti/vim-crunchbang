# vim-crunchbang

[**CrunchBang**](https://distrowatch.com/table.php?distribution=crunchbang) (now [BunsenLabs](https://www.bunsenlabs.org/)) was a lightweight Linux operating system with a sharp modern grey colour scheme.

**vim-crunchbang** is a Vim (and terminal) theme made of CrunchBang greys and complementary muted accent colours.

<img src="screenshot.png" alt="screenshot of vim-crunchbang, a cool grey vim theme" width="256">

## installation

### step 1: download the colour scheme

#### option A: manually

Download the desired [colourscheme files](https://github.com/nightsense/vim-crunchbang/tree/master/colors) and place in directory `~/.vim/colors/` (Linux/Mac) or `%userprofile%\vimfiles\colors\` (Windows).

#### option B: using a plugin manager

For easy management of Vim colour schemes (and other plugins), try a plugin manager. With [vim-plug](https://github.com/junegunn/vim-plug), for instance, just add `Plug 'nightsense/vim-crunchbang'` to the list of plugins in the `vimrc` file, then run `PlugUpdate`.

### step 2: activate the colour scheme

To activate the crunchbang theme, add `colorscheme crunchbang` to the `vimrc` file.

For Neovim, add `set termguicolors` to enable truecolour support.

### step 3: configure terminal colours (if using Vim in a terminal)

In order for crunchbang to work properly in terminal Vim, set the terminal's colours to match those of the active Vim theme.

As of now, this repository provides the following [terminal configuration files](https://github.com/nightsense/crunchbang/tree/master/terminal):
- [`Xresources`](https://github.com/nightsense/seabird/tree/master/terminal/Xresources) file for **xterm** and **urxvt** (Linux)
- [`gsettings`](https://github.com/nightsense/seabird/tree/master/terminal/pantheon-terminal.md) 'command blocks' for **pantheon-terminal** (elementary OS)
