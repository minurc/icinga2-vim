# icinga2-vim

## Clone from https://github.com/Icinga/icinga2/tree/master/tools/syntax/vim



Icinga 2 Configuration Vim Syntax Highlighting
==============================================

$ PREFIX=~/.vim
$ mkdir -p $PREFIX/{syntax,ftdetect}
$ cp syntax/icinga2.vim $PREFIX/syntax/
$ cp ftdetect/icinga2.vim $PREFIX/ftdetect/

Modify 'ftdetect/icinga2.vim' if your configuration isn't located in
'/etc/icinga2'.

Now test it :-)

$ vim /etc/icinga2/conf.d/templates.conf

