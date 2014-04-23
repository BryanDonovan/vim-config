vim-config
==========

My personal vim config for MacVim.  Might also work with other GUI-based Vim
clients. Based on the .vimrc from [Wolfy87/vim-config](https://github.com/Wolfy87/vim-config).

Setup:

    # Back up your existing .vimrc and .vim dirs.
    mkdir vim-backup
    mv .vimrc vim-backup
    mv .vim vim-backup
    git clone https://github.com/BryanDonovan/vim-config.git vim-config
    ln -s vim-config/vimrc .vimrc
    ln -s vim-config/vim .vim
    git clone http://github.com/gmarik/vundle.git vim-config/vim/bundle/vundle

Open a vim session and type :BundleInstall

This config uses [PeepOpen](http://topfunky.github.io/PeepOpen/) to easily
navigate your project.

I've found that MacVim works best with this config, and especially with
PeepOpen if you change some preferences:

* Set "Open files from applications" to "in the current window"
* Choose "and set the arglist"
