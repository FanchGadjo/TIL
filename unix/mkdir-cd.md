# Perform mkdir and cd using a single command

Merge both commands into a bash function and saved :

`̀``
echo 'mkcd() { mkdir -p "$@" && cd "$_"; }' >> ~/.bashrc
```

http://www.commandlinefu.com/commands/view/4566/mkdir-cd-into-it-as-single-command
