# Linux Training VM

This project helps to create Linux VM for [System Programming for Linux Containers Training M7D-SPLC02](http://man7.org/training/sys_prog_lxcon/index.html) course

## Pre-requirements

- [macOS](https://en.wikipedia.org/wiki/MacOS) 10.12 Sierra or higher
- [Homebrew](https://brew.sh/)

## Installation

- Checkout repo on your local machine
- Install [VirtualBox](https://www.virtualbox.org/)
  `brew cask install virtualbox`
- Install [Vagrant](https://www.vagrantup.com/intro/index.html)
  `brew cask install vagrant`
- Run
  `make vm`
- SSH onto machine
  `vagrant ssh`