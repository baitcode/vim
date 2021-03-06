My VIM config I use for Python development

To install just enter next commands:

    cd ~
    git clone git://github.com/satyrius/vim.git .vim
    ln -s .vim/vimrc .vimrc
    cd .vim
    git submodule init
    git submodule update

I use very few plugins and manage them using Pathogen. I prefer git submodules to be up-to-date with my plugins. My favourite plugins are:

* [Ropevim](http://rope.sourceforge.net/ropevim.html), a very powerful refactoring (but not only) tool;
* [Buffer Explorer](http://www.vim.org/scripts/script.php?script_id=42), you will love it if you prefer work with buffers instead of tabs;
* [Ctrl-P](http://www.vim.org/scripts/script.php?script_id=3736), fuzzy finder written in pure Vimscript;
* [Pyflakes](http://www.vim.org/scripts/script.php?script_id=3161), allow to run pyflakes on python files;

Your vim should bu built with +ryby and +python options. And following python modules should by installed to satisfy *ropevim* and *pyflakes* requirements. You should install them for python you have used to built into vim.

    pip install ropemode
    pip install ropevim
    pip install pyflakes

VIM or DIE!
