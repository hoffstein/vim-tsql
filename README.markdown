## SQL Server 2005/2008 syntax file for Vim

Author:  Benjamin Hoffstein  
Contact: ben@hoffstein.net


### INSTALLATION

1. Put the sqlserver.vim file in your syntax directory.

    * On Windows, this is $VIM/vimfiles/syntax or $HOME/vimfiles/syntax.
    * On Linux, this is $HOME/.vim/syntax or $VIM/vimfiles/syntax.

2. If you want to make this your default syntax file for .sql files, add the following to your vimrc:

    <code>let g:sql_type_default = "sqlserver"</code>

3. If you want to associate this syntax file with another extension, add the following to your vimrc (replace "ext" with the desired extension):

    <code>au BufNewFile,BufRead *.ext set filetype=sqlserver</code>

4. The file contains instructions for enabling/disabling several highlighting options (for example, system stored procedures). By default, all syntax is highlighted.

