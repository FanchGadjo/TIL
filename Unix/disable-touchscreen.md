```
xinput | grep 'ELAN Touchscreen' | grep -Po 'id=\d+' | cut -d= -f2 | xargs -i xinput --disable {}
```

http://askubuntu.com/questions/198572/how-do-i-disable-the-touchscreen-drivers
