# Vim

Vim is a highly configurable text editor built to make creating and changing any kind of text very efficient. It is included as "vi" with most UNIX systems and with Apple macOS.

Installation

To install the latest version, use homebrew:

```sh
brew install vim
```

The Ultimate vimrc

The Ultimate vimrc it's a collection of vimrc configurations to make easy the usage of vim.

To download the The Ultimate vimrc, you need to install the git client. If you need install it, use home brew:
```s
brew install git
```
Now, download the vimrc files:

```s
git clone https://github.com/amix/vimrc.git ~/.vim_runtime
```
To install the complete version, run:

```s
sh ~/.vim_runtime/install_awesome_vimrc.sh
```
To install the basic version, run:

```s
sh ~/.vim_runtime/install_basic_vimrc.sh
```
Update

To update the vimrc scripts, run:

```s
cd ~/.vim_runtime && git pull --rebase && cd -
```
Maximum Awesome

Maximum Awesome it's a collection of vim configuration and plugins, like a configuration manager for the vim environment.

Installation

To install it, just make a clone of the repository with the git client:

```s
git clone https://github.com/square/maximum-awesome.git
```
Then install it:

```s
cd maximum-awesome
rake
```
NOTE: the rake command will install all dependencies needed.
