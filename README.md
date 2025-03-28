# Feihong's asdf quickstart

## Install

Download from git repo

    brew install asdf

Add to `~/.zshrc`

    export PATH="${ASDF_DATA_DIR:-$HOME/.asdf}/shims:$PATH"
    
## Example

Download and install Node.js

    asdf plugin add nodejs
    asdf install nodejs latest
    asdf global nodejs latest # running `node` will run the latest version
    asdf list nodejs # see what versions you have

## Commands

Update asdf to latest version

    brew upgrade asdf

Show version of asdf

    asdf version

See what plugins you have installed

    asdf plugin list
    
See all available plugins

    asdf plugin list all
    
Add the Python plugin

    asdf plugin add python

Remove the Elixir plugin

    asdf plugin remove elixir
    
Install the latest version of Elixir

    asdf install python latest
    
Set the Python global version to the latest version

    asdf set -u python latest
    
List the Python versions you have installed

    asdf list python

List all Python versions that are available

    asdf list all python

Uninstall version 19.8.1 of Node.js

    asdf uninstall nodejs 19.8.1
    
## Links

- [asdf getting started](https://asdf-vm.com/guide/getting-started.html)
