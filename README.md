# [www.olimn.com](https://www.olimn.com)

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

### TODOs:
- Link some iframe spreadsheets
- what other kind of iframes are there?
- make a site map thing
- make music? No.



### Acknowledgements
Currently the website is 90% ChatGPT 4o-mini-generated - merely a time-saver. Thank you to all the web developers for providing data to the model, intentionally or not.
