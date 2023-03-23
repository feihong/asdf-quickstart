# Feihong's asdf quickstart

## Install

Download from git repo

    git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.11.3
    
Add the following to `~/.zshrc`

    . $HOME/.asdf/asdf.sh
    
## Commands

Update asdf to the latest stable release

    asdf update

See what plugins you have installed

    asdf plugin list
    
See all available plugins

    asdf plugin list all
    
Add the Elixir plugin

    asdf plugin add elixir
    
Install the latest version of Elixir

    asdf install elixir latest
    
Set the Elixir global version to the latest version

    asdf global elixir latest
    
List the Elixir versions you have installed

    asdf list elixir
    
## Links

- [Official download](https://asdf-vm.com/guide/getting-started.html#official-download)
