First, add a symbolic link to this directory:

    $ ln -s /path/to/dotfiles/vim ~/.vim

Edit your ~/.vimrc file to contain

    runtime vimrc

to load the `vimrc` file in this directory.
