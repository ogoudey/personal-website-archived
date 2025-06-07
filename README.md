# www.olimn.com

## Pushing to the Website
Pushing stuff to the website means pushing to the hosting service [nearlyfreespeech.net](https://www.nearlyfreespeech.net/).

This is how I do it, with [rsync](https://linux.die.net/man/1/rsync):
```
$ rsync <files to add> oling_olimn@ssh.nyc1.nearlyfreespeech.net: -a
```
Specifically, most often this is (copy this to update a webpage):
```
$ rsync src/html/* oling_olimn@ssh.nyc1.nearlyfreespeech.net: -a
```
It will then ask for a password, then the files will fly over to NFSN's servers.

## Outdated-ness
This is an simple, minimalist way to maintain a website. It is also very transparent/public-facing - which is good!

As of 6/7/25 this method is no longer used.
