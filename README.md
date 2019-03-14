# vim
vim configuration and commands

#   steps to install vim plug
step 1. run on terminal :
    curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
    
    <a href="https://github.com/junegunn/vim-plug"> refring </a>
    
step 2. create a .vimrc file in home directory > put basic vim cofig(can be used this repo .vimrc content) > open vim in terminal > press : > write plug (to check for more plug option press tab) > finaly use plugInstall to install plugin

##  VIM commands:-
    Press d to cut y to copy p to paste -vim
    > for indent and < for unindent in command mode
    ctrl+T for indent and ctrl+D for unindent in insert mode
    v+arrow key to select any where
    F2 to open project tree
    Crtl x and then o to autocomplete

    ======Delete space vim=======
    delete space vim folder and uninstalled successfully
    --------------------------------------------------------------------------
    curl -sLf https://spacevim.org/install.sh | bash -s -- --uninstall

    Useful commands
    How to close Vim
    :q to quit
    :q! to force quit
    :wq to save and quit
    Command Actions
    d : delete
    i : insert
    p : put / paste
    y : yank / copy
    x : cut
    u : undo
    di: delete inside*, yi : yank inside*
    v : visual / selection
    / : search
    % : parentheses matching, developers rejoice!
    :s : substitute! In other words, find-replace on steroids
    To delete the current line: dd
    To copy the current line: yy
    w : beginning of next word (we’ve seen this before!)
    e : ending of current word
    b : beginning of previous word
    $ : end of line
    0 : beginning of line
    G : end of file
    nG : jump to line number n
    ) : jump forward a sentence
    } : jump forward a paragraph
    Split screen
    :vsplit <filename>
    To cycle between screen-splits: <ctrl-w> <ctrl-w>
    You can close windows as you normally do (:q), or —
    :only — to close all other windows
    => indent
    in command mode select using presing v and arrow key and press =
    in insert mode press ctrl t and ctrl d
