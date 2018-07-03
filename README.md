
# dedukti-editor [![Build Status](https://travis-ci.com/lachhebo/dedukti-editor.svg?branch=master)](https://travis-ci.com/lachhebo/dedukti-editor)


## Installation

You need Atom >= 1.19.

```
$ apm install lachhebo/dedukti-editor
```

### Installing the Dedukti Language Server:

The easiest method is to use the [OPAM](https://opam.ocaml.org/) package manager:
```
$ opam repository add deducteam https://scm.gforge.inria.fr/anonscm/git/opam-deducteam/opam-deducteam.git
$ opam install lambdapi-lsp
```


## Utilisation

- with this version of dedukti-editor, you can check and write your proofs.

## Debug :

To debug, open a developper console (Ctrl+Shift+I) and set the filter to verbose.

## ToDo :

- implement a new command to handle the view.
- implement goals on the view
- add an action for each button

## Keybindings :

| Key |  Action |
|--|--|
| ctrl-alt-p | Next step |
| ctrl-alt-m | Last step |
