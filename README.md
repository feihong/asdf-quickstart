# Feihong's asdf quickstart

## Install

Download from git repo

    git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.13.1
    
Add the following to `~/.zshrc`

    . $HOME/.asdf/asdf.sh
    
## Example

Download and install Node.js

    asdf plugin add nodejs
    asdf install nodejs latest
    asdf global nodejs latest # running `node` will run the latest version
    asdf list nodejs # see what versions you have

## Commands

Update asdf to the latest stable release

    asdf update

Show version of asdf

    asdf version

See what plugins you have installed

    asdf plugin list
    
See all available plugins

    asdf plugin list all
    
Add the Elixir plugin

    asdf plugin add elixir

Remove the Elixir plugin

    asdf plugin remove elixir
    
Install the latest version of Elixir

    asdf install elixir latest
    
Set the Elixir global version to the latest version

    asdf global elixir latest
    
List the Elixir versions you have installed

    asdf list elixir

List all Node.js versions that are available

    asdf list all nodejs

Uninstall version 19.8.1 of Node.js

    asdf uninstall nodejs 19.8.1
    
## Links

- [Official download](https://asdf-vm.com/guide/getting-started.html#official-download)
