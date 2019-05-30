# vIDE : A snappy IDE for Competitive Programming
A beautiful customizable IDE based on Vim
  
## Pre-requisites
Vim (obviously)\
Python\
Basic terminal knowledge

## Installation (Linux)
### Step 1:
Open terminal and execute the following
```
git clone https://github.com/Enixes/vIDE.git 
```
### Step 2:
```
cd vIDE/
```
### Step 3:
Copy the vimrc file to ~/ (root directory)
```
cp .vimrc ~/
```
### Step 4:
Copy the .vim to root directory
```
cp -R .vim/ ~/
```
### Step 5:
Make a new project directory and copy the .ycm_extra_conf.py  to the same \
This will enable the code completion (YouCompleteMe) for the files in the project directory\
For example:
```
mkdir ~/MyCppfiles
```
```
cp .ycm_extra_conf.py ~/MyCppfiles
```
### Step 6:
Install Plugin Manager Vundle
```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
Finally the last step, bare with me
### Step 7:
Now run vim and ignore the errors and press ENTER\
Now type and wait about 10 minutes for all the plugins to install.
```
:PluginInstall
```
### Restart vim and enjoy your new personal IDE
For VIM shortcuts:
https://www.maketecheasier.com/vim-keyboard-shortcuts-cheatsheet/
