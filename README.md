
# ki.vim

This vim plug-in provides minimalist support for the [ki language][ki]

Mostly, right now, it sets the filetype to 'clojure' automatically
when you open a `.ki` or `.ki.js` file. Support might be extended
later on with proper highlighting, comments, error checking, etc.

For this plugin to work, you'll need [vim-clojure-static][vcs] -
or a sufficiently version of vim that ships it.

## Install instructions

[Vundle][vundle] is a very neat tool to manage your vim plugins, and
is the recommended way to get ki.vim and keep it up-to-date.

Add this to your `~/.vimrc`:

```viml
Bundle 'memoways/ki.vim'
```

Then restart vim, run `:BundleInstall`, and you're set!

Installing ki.vim with pathogen should be as easy as cloning it in
`~/.vim/bundle`

[ki]: http://ki-lang.org/
[vcs]: https://github.com/guns/vim-clojure-static
[vundle]: https://github.com/gmarik/Vundle.vim

