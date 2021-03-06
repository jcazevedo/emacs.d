# Joao Azevedo's Emacs-specific files

This directory tree contains Joao Azevedo's Emacs-specific files.

## Installing

These files can usually be obtained by cloning the repository at
`git@github.com:jcazevedo/.emacs.d.git`. You need to ensure that the `init.el`
file ends up at `~/.emacs.d/init.el`. You can either do that by cloning directly
to that folder:

    $ git clone git@github.com:jcazevedo/.emacs.d.git ~/.emacs.d

or by cloning somewhere else and creating a symlink there. I usually keep all my
projects under the `~/work` folder, and as such, I symlink this project
directory to `~/.emacs.d`:

    $ git clone git@github.com:jcazevedo/.emacs.d.git ~/work/emacs.d
    $ ln -s ~/work/emacs.d ~/.emacs.d

When starting Emacs for the first time, third-party packages should be
automatically downloaded and installed. If you encounter any errors at that
stage, run `M-x package-refresh-contents` and restart Emacs.

## Updating

When updating, you generally should only need to do a `git pull`, followed by a
third-party packages update. For the latter, run `M-x package-list-packages`,
then `U` followed by a `x`.

## License

See LICENSE.md
