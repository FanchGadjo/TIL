# Configure git to push-pull tags

Pour toujours envoyer/recevoir les tags (versions) :

```
git config --global push.followTags true
git config --global remote.origin.tagopt --tags
```

https://stackoverflow.com/questions/3745135/push-git-commits-tags-simultaneously
https://stackoverflow.com/questions/12533890/how-can-you-configure-git-to-automatically-fetch-the-tags-on-every-pull
