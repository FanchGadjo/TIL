# Using bash history
if you run a command that needs root privileges but forget to add `sudo` to the beginning, there's no need to retype the command. Just run:
```
sudo !!
```

If you just want to see what the last cat command was, you can instead run:
```
!cat:p
```

If you want to run a different command that you ran last, but with the same argument, there's a shortcut for that too. For example, say you had just created a folder using:
```
mkdir /new/awesome/folder
```
To then cd into that directory, you could just type:
```
cd !$
```
The `!$` represents the arguments from your last command.

Another common problem is mistyping the command you want to run. Say you wanted to run `nano`, but accidentally typed `nanp`:
```
nanp /path/to/a/document/buried/deep/in/the/filesystem
```
Instead of retyping the whole thing, you could just run:
```
^nanp^nano
```

If you want to see all the recent commands you ran that included `nano`, for example, you could just run:
```
history | grep nano
```
You'll get a list that looks something like this:
```
381 sudo nano /etc/NetworkManager/nm-system-settings.conf
387 sudo nano /etc/rc.conf
388 sudo nano /etc/rc.conf
455 sudo nano /boot/grub/menu.lst
```
You can then pick a command out from that list—say I want to run `sudo nano /boot/grub/menu.lst`, which grep lists as command `455`—and run it using:
```
!455
```
