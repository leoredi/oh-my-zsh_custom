oh-my-zsh_custom
================

This repo verions [oh-my-zsh][] custom directory ($HOME/.oh-my-zsh/custom/) taking inspiration from [oh-my-zsh-custom][]

[oh-my-zsh]: https://github.com/robbyrussell/oh-my-zsh
[oh-my-zsh-custom]: https://github.com/nishigori/oh-my-zsh-custom

Usage
-----

## Install

```sh
cd ~/.oh-my-zsh
git rm -rf custom
git submodule add https://github.com/leoredi/oh-my-zsh_custom.git
git commit -m 'Inject custom directories'
```

## Update oh-my-zsh

```sh
cd ~/.oh-my-zsh
git pull --rebase
```

## Create your original plugin

When create plugin but OS Dependency, Please put plugin file to `~/.oh-my-zsh/custom/os/{YOUR_OSTYPE}`

When create plugin but local Machine Dependency, Please put plugin file to `~/.oh-my-zsh/custom/local`

Local dependency
----------------

If you have local environment dependency and private settings,
puts the local directory (*.zsh)

for example,

    $ ls ./local

    alias.zsh   autojump.zsh
