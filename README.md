vim
===

vim configuration

details: https://github.com/gmarik/vundle


-----


Usage
=====

* copy the two files(.vimrc and .bash-aliases) into the home directory;
* uncompress the vim.tar.gz and copy the directory 'vim' to home directory;
* make sure the tools ctags and cscope already installed;
* Go to the top directory of your project, run the two commands:
    1. generate tags file:```map key ,<F12>``` OR ```ctags_n . /usr/include /usr/local/include```
    2. generate cscope DB:```map key ,<F11>``` OR ```cscope_n -I.  -I/usr/include  -I/usr/local/include```
* run vim
