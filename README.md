# mmv

A zsh alias to move multiple files with ease. Credits go to [Marios
Braindump](http://www.mfasold.net/blog/2008/11/moving-or-renaming-multiple-files/).

## Installation

### With oh-my-zsh

1. Clone it to the custom plugins folder

  ```
  git clone git@github.com:rathrio/mmv.git ~/.oh-my-zsh/custom/plugins/mmv
  ```

2. Register it as a plugin in `.zshrc`

  ```
  plugin=(... mmv)
  ```

3. Source `.zshrc` to load changes

  ```
  source ~/.zshrc
  ```

### Without oh-my-zsh

Clone this repo and source `mmv.plugin.zsh` in your `.zshrc`.

## Usage

* Change all `.css.scss` file endings to `.css`

  ```
  mmv *.css.scss *.scss
  ```

* Backup all ruby files

  ```
  mmv *.rb *.rb.backup
  ```
