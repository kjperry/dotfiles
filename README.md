Dotfiles. Almost entirely a shameless cribbing of @braintreeps'
[vim_dotfiles](https://github.com/braintreeps/vim_dotfiles) and @mikepilat's
[tmux.conf](https://github.com/mikepilat/dotfiles/blob/master/tmux.conf).


After cloning this project, you can run the following to link these dotfiles
into your home directory:

```
bundle install
rake
```

Be warned: this will overwrite any existing .tmux.conf, .vimrc, .gvimrc or .vim/ files you
have in your home directory.

Uses `vim-plug` to manage bundles. Downloading and setting up the described
plugins requires an extra step:

```
vim +:PlugInstall
```

If you plan on using command-t, you'll need to build the C extension. Make sure
to use the ruby you built vim against:

```
rvm use system
```
