config:
step1 cd ~
step2 mv spf13-vim-3 .spf13-vim-3
step3 mv vim .vim

ln -s .spf13-vim-3/.vimrc  .vimrc
ln -s .spf13-vim-3/.vimrc.before   .vimrc.before
ln -s .spf13-vim-3/.vimrc.bundles  .vimrc.bundles

