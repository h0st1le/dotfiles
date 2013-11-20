dotfiles for homeshick
======================

my dotfiles for deployment using [homeshick](https://github.com/andsens/homeshick.git)

### Requirements
* [git](http://git-scm.com/)
* [zsh](http://www.zsh.org/)
* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh.git)
* [homeshick](https://github.com/andsens/homeshick.git)
* [vim](http://www.vim.org/)
* [vundle](https://github.com/gmarik/vundle)

### Installation

Install zsh, vim and git

    sudo apt-get install zsh vim vim-gnome git

Set zsh as the default shell

	chsh -s /bin/zsh

Install oh-my-zsh

	git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh

Install Vundle

	git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle

Install homeshick

	git clone git://github.com/andsens/homeshick.git $HOME/.homesick/repos/homeshick

Clone the castle

	$HOME/.homesick/repos/homeshick/bin/homeshick clone https://github.com/h0st1le/dotfiles.git

Initialize and install Vim bundles

    vim +BundleInstall +qall
