# Beer song

99 Bottles of Beer is an algorithmic children's song which has just enough complexity to teach you deep truths about object oriented programming.

Our goal is to produce the lyrics to that beloved classic, that field-trip favorite. You can find them @ [`dcarral/99bottles-polyglot/SONG_LYRICS.md`](https://github.com/dcarral/99bottles-polyglot/blob/master/SONG_LYRICS.md).

## Setup

Check out [Exercism Help](http://exercism.io/languages/lisp) for instructions to
get started writing Common Lisp. That page will explain how to install and setup
a Lisp implementation and how to run the tests.

## Formatting

While Common Lisp doesn't care about indentation and layout of code, using only spaces is recommended to make
the code more readable to the human reviewers. Please review your
editors settings on how to accomplish this. Below are instructions for
popular editors for Common Lisp.

### VIM

Use the following commands to ensure VIM uses only spaces for
indentation:

```vimscript
:set tabstop=2
:set shiftwidth=2
:set expandtab
```

(or as a oneliner `:set tabstop=2 shiftwidth=2 expandtab`). This can
be added to your `~/.vimrc` file to use it all the time.

### Emacs

Emacs is very well suited for editing Common Lisp and has many
powerful add-on packages available. The only thing that one needs to
do with a stock emacs to make it work well with exercism.io is to
evaluate the following code:

`(setq indent-tab-mode nil)`

This can be placed in your `~/.emacs` (or `~/.emacs.d/init.el`) in
order to have it set whenever Emacs is launched.

One suggested add-on for Emacs and Common Lisp is
[SLIME](https://github.com/slime/slime) which offers tight integration
with the REPL; making iterative coding and testing very easy.
