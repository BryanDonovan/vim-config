vim-config
==========

My personal vim config

Setup:

    mkdir vim-backup
    mv .vimrc vim-backup
    mv .vim vim-backup
    git clone https://github.com/BryanDonovan/vim-config.git vim-config
    ln -s vim-config/vimrc .vimrc
    ln -s vim-config/vim .vim
    git clone http://github.com/gmarik/vundle.git vim-config/vim/bundle/vundle

Open a vim session and type :BundleInstall

