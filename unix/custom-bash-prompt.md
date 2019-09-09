# Custom bash prompt

generators :
http://bashrcgenerator.com/
http://omar.io/ps1gen/

for root :
https://unix.stackexchange.com/questions/366361/how-to-customize-the-prompt-for-root

with git :
https://blog.smarchal.com/bash-prompt-personnalise

```
export PS1="\n\[$(tput sgr0)\]\[\033[38;5;2m\]\u@\h\[$(tput sgr0)\]\[\033[38;5;0m\]:[\[$(tput sgr0)\]\[\033[38;5;6m\]\w\[$(tput sgr0)\]\[\033[38;5;0m\]]\[$(tput sgr0)\]\[\033[38;5;15m\]\n\[$(tput sgr0)\]\[\033[38;5;0m\]\\$\[$(tput sgr0)\]\[\033[38;5;15m\] \[$(tput sgr0)\]"
```
Root :
```
export PS1="\n\[$(tput sgr0)\]\[\033[38;5;255m\]\[\033[48;5;1m\]\u@\h\[$(tput sgr0)\]\[\033[38;5;0m\]\[\033[48;5;-1m\]:[\[$(tput sgr0)\]\[\033[38;5;6m\]\w\[$(tput sgr0)\]\[\033[38;5;0m\]]\[$(tput sgr0)\]\[\033[38;5;15m\]\n\[$(tput sgr0)\]\[\033[38;5;0m\]\\$\[$(tput sgr0)\]\[\033[38;5;15m\] \[$(tput sgr0)\]"
```
