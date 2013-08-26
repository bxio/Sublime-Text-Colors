# [Bill Xiong's](http://billxiong.com) [Sublime Text 3](http://www.sublimetext.com/3) Colour Schemes
---------------------
[Sublime Text](http://www.sublimetext.com/) is my main editor. This is just a Backup of my Color Themes.

## Installation

### Sublime Text 3

For the sublime text 3 editor the themes can be installed easily by using [Package Control](http://wbond.net/sublime_packages/package_control) to install the 'Dayle Rees Color Schemes' package from the official repository.

Otherwise, first find your Sublime Text 2 packages directory, you can find this by using the `Preferences -> Browse Packages` menu from within Sublime Text 2.

Now either create a `bxio - themes` folder within this directory, and copy the contents of the github repository inside, or clone the repo using the GIT software within the packages directory :

	git clone https://github.com/bxio/sublime-text-colors.git Color Scheme

Now simply use the `Color Schemes` option of your preferences menu to switch between themes, enjoy!

### VIM

## Manual

Download or clone with git, the themes into your `.vim/colors` directory.

## Vundle

Add the following to your `.vimrc`:

```viml
Bundle "bxio/colour-schemes", { "rtp": "vim-themes/" }
```

Either way you install it, just add the following line to your `.vimrc`:

```viml
colorscheme <scheme-name-here>
```

Save and launch vim to use, enjoy!
