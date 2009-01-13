SQL Server 2005/2008 syntax file for Vim
========================================

Author:  Benjamin Hoffstein
Contact: benjamin.hoffstein AT red-hook DOT com


DOWNLOAD
--------

The latest version of the file is always available on Vim.org:

http://www.vim.org/scripts/script.php?script_id=2449


INSTALLATION
------------

1. Put the sqlserver.vim file in your syntax directory.

    * On Windows, this is $VIM/vimfiles/syntax or $HOME/vimfiles/syntax.
    * On Linux, this is $HOME/.vim/syntax or $VIM/vimfiles/syntax.

2. If you want to make this your default syntax file for .sql files, add the following to your vimrc:

    let g:sql_type_default = "sqlserver"

3. If you want to associate this syntax file with another extension, add the following to your vimrc (replace "ext" with the desired extension):

    au BufNewFile,BufRead *.ext set filetype=sqlserver

4. The file contains instructions for enabling/disabling several highlighting options (for example, system stored procedures). By default, all syntax is highlighted.

