# .dotfiles
The .dotfiles I use for my setup

## Setup
Scripts work with bash, on MacOS. YMMV

Super simple setup script for oh-my-zsh

## Pre-requisites
- Intsall oh-my-zsh

## Install

- Running `./install` will do the following
  - `mv ~/.zshrc ~/.zshrc.backup`
  - `cp ~/.dotfiles/.oh-my-zsh/.zshrc ~/.zshrc`
  
  ### Other Notes
  This project has a post-checkout git hook.
  
  If you edit this project in IntelliJ etc. you need to disable Intellij hiding the .git folder.
  
  Open Preferences, and in the search type 'ignore file' and under File Types, remove .git from the string
