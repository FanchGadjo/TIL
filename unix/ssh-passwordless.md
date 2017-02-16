# Configure passwordless ssh login

Install `sshpass`
```
sudo apt-get install sshpass
```

Example :
```
sshpass -p 'P@ssw0rd' ssh sk@192.168.1.150
```

export the password to Environment variable 
```
export SSHPASS=P@ssw0rd
```

```
sshpass -e ssh sk@192.168.1.150
```

Set env var permanently :
```
$EDITOR ~/.bashrc
#add lines at the bottom of the file:
    export SSHPASS=P@ssw0rd
```

---
http://www.muktware.io/configure-passwordless-ssh-login-linux/
http://unix.stackexchange.com/questions/117467/how-to-permanently-set-environmental-variables
