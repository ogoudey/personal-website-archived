## Pushing to the website.
Pushing stuff to the website means pushing to the hosting service https://www.nearlyfreespeech.net/

This is how I do it:
```
>>> rsync <files to add> oling_olimn@ssh.nyc1.nearlyfreespeech.net: -a
```

It will then ask for a password, and the files will fly over to their servers.
