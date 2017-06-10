# vim-js

Collection of settings and plugins to work effectively with JS.

# Workflows

- maybe animated gifs for things you commonly do

# General Plugins

Make use of the following template when adding plugins:

```
## [Name](http://github.com/...)

it does the following

### Features
### Options
### Missing Things
```
Feel free to open an issue if you have suggestions for improvement.

## [vim-javascript](https://github.com/pangloss/vim-javascript)

vim-javascript is a bundle which improve default JavaScript syntax highlighting
and indentation. It provides syntax highlight for modern JavaScript features and
is maintained by an active community.

### Features

- provides syntax highlight for modern features of JavaScript.
- improves default indentation for JavaScript's filetype.
- use `eslint` as the default compiler.
- set `filetype` to `javascript` for files ending with `js, jsm, es, es6` as
  as well as scripts which have a node shebang.
- supports [flow](https://flow.org) through `g:javascript_plugin_flow` option.
- supports [JSDoc](http://usejsdoc.org/) throug `g:javascript_plugin_jsdoc`
  option.
- suports [ngdoc](https://github.com/angular/angular.js/wiki/Writing-AngularJS-Documentation)
  through `g:javascript_plugin_ngdoc` option.
- adds JavaScript ctags patterns.

### Options

- `let g:javascript_plugin_jsdoc`: enables JSDoc syntax highlight.
- `let g:javascript_plugin_jsdoc`: enables ngdoc syntax highlight.
- `let g:javascript_plug_flow`: enables flow syntax highlight.

### Missing Things

This plugin mainly covers syntax highlight and indentation with some extras. It
doesn't provide any linter, neither syntax completion for most JavaScript /
frameworks / librairies like `node.js`, `Angular`, `React`, `Vue`, `Electron`...

# Ressources

- links to external pages

# Frameworks

## React

### Plugins

## Webpack

### Plugins
