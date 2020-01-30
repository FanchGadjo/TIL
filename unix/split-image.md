# Split image

Split images in half from an `src` folder with `imagemagick` :

```
ls -1 src | xargs -i convert src/{} -crop 2x1@ +repage {}
```

https://www.imagemagick.org/discourse-server/viewtopic.php?t=33208
