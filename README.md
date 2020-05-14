Discontinued in favor of https://github.com/antonmry/dotfiles/blob/master/dot_vimrc

-----------------------------------

# vim

The Vim configuration I'm using in my laptop.

### 0. What is this?

A bunch of scripts, plugins and more to configure in seconds my local vim.

### 1. Install runtime:

Fork the repo, and then clone it to `~/.vim_antonmry_runtime`. Once done, just run installation script:

    git clone git@github.com:antonmry/vim.git ~/.vim_antonmry_runtime
    sh ~/.vim_antonmry_runtime/bin/install

**NOTE:** You system's Vim configuration will NOT be changed i.e. it is safe to install.

### 2. Run your newly installed Vim configuration:

Remember that your system's Vim config files remain untouched? During installation `.vimrc.antonmry` is created. Let's use it:

    vim -u ~/.vimrc.antonmry

And btw, nothing prevents you from creation of a handy alias in your `.bash_aliases`:

    alias vim='vimx -u ~/.vimrc.antonmry'


You can also define your custom settings in `~/.vim_antonmry_runtime/custom_config.vim` the runtime will try to load this file - so feel free to remap keys as you see necessary!

**If you know some plugin that will enhance this setup and thus should be included - submit a PR**
