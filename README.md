# zsh-aliases-easy-remember

zsh-aliases easy to remember commands for terminals and servers - If you want to help me make bigger the list, you are welcome, just remember that:

1. The commands need to align to an ACTION example is we are going BACK in the folders structure, we find the command:
```
alias back="cd .."
```
2. Name them in camelCase first letter in lowercase

Enter into the area of alias (I call them snips = snippets)
```
nano ~/.zshrc
```
Copy paste
```zsh
alias snips="nano ~/.zshrc"
alias resetSnips="source ~/.zshrc"
alias resetTerminal="source ~/.zshrc"
alias create="touch"
alias createFolder="mkdir"
alias removeDirectory="rmdir"
alias b="cd .."
alias back="cd .."
alias home="cd /"
alias rename="mv"
alias delete="rm"
alias copy="cp"
alias move="mv"
alias show="cat"
alias list="ls -al"
alias goTo="cd"
alias enter="cd"
alias clean="clear"
alias cl="clear"
alias currentDirectory="pwd"
```

after paste, save the file and exit -> to termianl, run this to reset the terminal
```
# source ~/.zshrc
```
